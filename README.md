### Hey, I'm Jason! 👋
✉️ [Jason.moore@consultant.com](mailto:jason.moore@consultant.com)

```php
<?php

namespace JasonMoore;

class About extends Me
{
    /**
     * Define company info.
     * @const string
     */
    const COMPANY_NAME = 'Raviga';
    const COMPANY_ROLE = 'Product Manager';

    /**
     * Return workplace info.
     * @return array
     */
    public function getCurrentWorkplace(): array
    {
        return [
            'workplace' => [
                'company' => self::COMPANY_NAME,
                'role' => self::COMPANY_NAME
            ]
        ];
    }

    /**
     * Return daily activities.
     * @return array
     */
    public function getDailyActivities(): array
    {
        return [
            Php::class,
            Laravel::class,
            Vuejs::class,
            Bootstrap::class,
            Javascript::class,
            Css::class,
            Aws::class,
            Qa::class,
        ];
    }

    /**
     * Return future goal.
     * @return string
     */
    public function getFutureGoal(): string
    {
        return 'To build something amazing.';
    }
}
```
