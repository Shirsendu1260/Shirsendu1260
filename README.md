```php
<?php

class SoftwareDeveloper
{
    public string $name;
    public string $role;
    public string $location;
    public array $languages;
    public array $backend;
    public array $databases;
    public array $orm;
    public array $frontend;
    public array $tools;

    public function __construct(
        string $name,
        string $role,
        string $location,
        array $languages,
        array $backend,
        array $databases,
        array $orm,
        array $frontend,
        array $tools
    ) {
        $this->name = $name;
        $this->role = $role;
        $this->location = $location;
        $this->languages = $languages;
        $this->backend = $backend;
        $this->databases = $databases;
        $this->orm = $orm;
        $this->frontend = $frontend;
        $this->tools = $tools;
    }
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