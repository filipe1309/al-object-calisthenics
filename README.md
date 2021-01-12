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
- Wrap your prímitive types (if its has behavior)
- Fisrt class collections

## Tests

```
./vendor/bin/phpunit tests/
```
