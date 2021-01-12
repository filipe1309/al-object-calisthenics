# Object Calisthenics

## Dependencies

- PHP Extension DS

## Installation

```
composer install
```

## Rules

- [1] No Getters/Setters/Properties
  - If there is no business rule
  - Tell, Don't Ask
- [2] Only One Level Of Indentation Per Method
- [3] Don’t Use The ELSE Keyword
- [4] Wrap your prímitive types (if its has behavior)
- [5] Fisrt class collections
- [6] One Dot Per Line
  - SOLID Open-Close principle
  - Law Of Demeter  (don't talk with strangers!) http://wiki.c2.com/?LawOfDemeter
  -  Exception: Fluent interface
- [7] Don’t Abbreviate
- [8] Keep All Entities Small
  - Recommendation: Classes max 50 lines, packages max 10 classes
- [9] No Classes With More Than Two Instance Variables


## Tests

```
./vendor/bin/phpunit tests/
```
