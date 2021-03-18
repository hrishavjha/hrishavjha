```python
def intro_view(request):
    context = {
        'Name': 'Hrishav',
        'Profession': 'Student',
        'Adjective': 'Web Developer',
    }
    return render(request, 'Pages/Hello.html', context)
```
