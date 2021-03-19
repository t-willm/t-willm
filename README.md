### Hi there 👋

```php
<?php 

namespace TWillm;

class About extends Me
{
    public function getCurrentWorkplace(): array
    {
        return [
            'workplace' => [
                'company' => 'Freshmile Services',
                'position' => 'Laravel Backend Develop - DevOps',
            ],
        ];
    }

    public function getDailyKnowledge(): array
    {
        return [
            Php::class,
            Javascript::class,
            Laravel::class,
            Lumen::class,
            Vuejs::class,
            jQuery::class,
            MySQL::class,
            MariaDB::class,
            Nginx::class,
            Docker::class,
            GitlabCI::class,
            GitGitflow::class,
            UnitTests::class,
            Tdd:class,
            Devops::class,
        ];
    }

    public function getFutureGoals(): array
    {
        return [
            'Contribute to open source.',
            'Learn Ruby and Ruby On Rails',
            'Learn Python and Ansible',
            'Learn React',
        ];
    }
}
```