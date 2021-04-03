```php
<?php

namespace RamonJoaquim;

class About extends Me
{
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
            Php::class,
            Laravel::class,
            Aws::class,
            GitLab::class,
        ];
    }

    public function getFutureGoal(): string
    {
        return 'More knowledge and contribuite in openSource projects';
    }
    
    public function getPersonalProjectAddress(): string
    {
        return 'https://nomasys.com.br';
    }
}
```
