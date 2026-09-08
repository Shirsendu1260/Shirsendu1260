```php
<?php

class SoftwareDeveloper
{
    public function __construct(
        public string $name,
        public string $role,
        public string $location,
        public array $languages,
        public array $backend,
        public array $databases,
        public array $orm,
        public array $frontend,
        public array $tools
    ) {}
}

$shirsendu = new SoftwareDeveloper(
    'Shirsendu Mali',
    'Backend / Full Stack Developer',
    'Kolkata, West Bengal, India',
    ['PHP', 'TypeScript', 'JavaScript', 'SQL'],
    ['Laravel', 'Node.js', 'Express.js'],
    ['PostgreSQL', 'MySQL', 'MongoDB'],
    ['Eloquent', 'Drizzle ORM', 'Mongoose'],
    ['HTML', 'React', 'Tailwind CSS'],
    ['Git', 'Docker', 'Postman', 'Swagger UI']
);

?>
```
