## Planet Dates

### Description

1. Imagine, that humanity has colonized distant planets. Let's name one of the planets Red and another planet is Blue. On planet Red calendar has 10 months in a year, 42 days each month. On planet Blue they have 18 months 18 days each month. Consider, that chronology began at the same point in time on all planets (date 0001-01-01 happened simultaneously) and days have same length.
For a transplanetary Trading App you need to create a date converter for planets Red, Blue and Earth. Keep in mind, it should be extendable, as new planets may be added to the list.

2. Create a calculator, that can operate on dates. Required functions are: addDays($days), addMonths($months), addDate($date). For date addition, you should add years, months and days of the second date to the first. E.g. Earth Date:
   - 2019-08-13 addMonths(2) -> 2019-10-13
   - 2019-08-13 + 0002-02-01 -> 2021-10-14
It should work for all planets.
