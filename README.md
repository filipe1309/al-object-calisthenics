# Object Calisthenics

## Dependencies

- PHP Extension DS

## Installation

```
composer install
```

## Rules

- Dont use Getters and Setters, if there is no business rule
  - Tell, Don't Ask
- One level of identation by method
- NEVER use else

## Tests

```
./vendor/bin/phpunit tests/
```
