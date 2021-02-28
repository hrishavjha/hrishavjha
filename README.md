```php
<?php

namespace Hrishav;

class About extends Me
{
    public function getCurrentWorkplace(): array
    {
        return [
            'workplace' => [
                'Occupation' => 'Student',
                'About' => 'Web Developer'         
            ]
        ];
    }

    public function getDailyKnowledge(): array
    {
        return [
            Php::class,
            Javascript::class,
            React::class,
            ReactNative::class,
            Electron::class,
            TailwindCss::class,
            Aws::class,
            Django::class,
        ];
    }

    public function getFutureGoal(): string
    {
        return 'To compile a code w/o any error.';
    }
}
```
