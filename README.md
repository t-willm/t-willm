### Hi there 👋

```php
<?php 

namespace TWillm;

class About extends Me
{
    public function getCurrentStatus(): array
    {
        return [
            'status' => [
                'actualJob' => 'Laravel Backend Developer - DevOps',
                'resume' => 'Using Laravel, VueJS, Docker, also working on CI/CD and following DevOps movement',
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