```php
<?php

namespace RamonJoaquim;

class About extends Me
{
    public function getBio(): string 
    {
        return 'Bachelor in Information System, Full Stack Developer with knowledge about DevOps culture, 
        API development and also functional and automated tests.';
    }
    
    public function getCurrentWorkplace(): array
    {
        return [
            'workplace' => [
                'company' => 'Betha Sistemas',
                'position' => 'Full-Stack developer' 
            ]
        ];
    }

    public function getDailyKnowledge(): array
    {
        return [
            Java::class,
            AngularJS::class,
            Kubernetes::class,
            Javascript::class,
            MongoDB::class,
            React::class,
            NestJS::class,
            Aws::class,
            GitLab::class
        ];
    }

    public function getFutureGoal(): array
    {
        return [
            Flutter::class,
            Electron::class
        ];
    }
   
}
```
