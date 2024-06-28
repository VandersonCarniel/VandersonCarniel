## Hello World! 😁
<!--![Visitors Count](https://visitor-badge.glitch.me/badge?page_id=VandersonCarniel.visitor-badge&left_text=Visitors)-->

<!--GITHUB_ACTIVITY:{"rows": 5, "raw": true}-->


```php
<?php

namespace Vanso;

class About extends Me
{
    public function getCurrentWorkplace(): array
    {
        return [
            'workplace' => [
                'company' => 'Sicredi Vale do Cerrado 🍀',
                'position' => 'Assesor de BI'         
            ]
        ];
    }

    public function getDailyKnowledge(): array
    {
        return [
            Php::class,
            Javascript::class,
            Python::class,
            Laravel::class,
            Angular::class,
            ReactNative::class,
            TailwindCss::class
        ];
    }

    public function getFutureGoal(): string
    {
        return 'Cooperating with open-source';
    }
}
```
