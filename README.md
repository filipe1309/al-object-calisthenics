# Object Calisthenics

## Dependencies

- PHP Extension DS

## Installation

```
composer install
```

## Rules

- No Getters/Setters/Properties
  - If there is no business rule
  - Tell, Don't Ask
- Only One Level Of Indentation Per Method
- Don’t Use The ELSE Keyword
- One Dot Per Line
  - SOLID Open-Close principle
  - Law Of Demeter  (don't talk with strangers!) http://wiki.c2.com/?LawOfDemeter
  -  Exception: Fluent interface
- Don’t Abbreviate

## Tests

```
./vendor/bin/phpunit tests/
```
