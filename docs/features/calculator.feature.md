# Feature: Calculator


Lorem ipsum dolor

## Rule: rule 1


### Background: Background name 

* Given the Calculator

### Scenario: Add two numbers

* Given the 'first' number is '50'
* And the 'second' number is '70'
* When the two numbers are 'added'
* Then the result should be '120'

## Rule: rule 2


### Scenario: Substract two numbers

* Given the 'first' number is '50'
* And the 'second' number is '25'
* When the two numbers are 'subtracted'
* Then the result should be '25'

## Rule: rule 3

lorem ipsum dolor

`@important` `@essential`
### Scenario Outline: Multiply two numbers

* Given the 'first' number is '\<first value\>'
* And the 'second' number is '\<second value\>'
* When the two numbers are 'multiplied'
* Then the result should be '\<result\>'

#### Examples:


  | first value | second value | result |
  |-------------|--------------|--------|
  | 2           | 2            | 4      |
  | 3           | 2            | 6      |

## Rule: rule 4


### Scenario: Add numbers

* Given the following numbers

  | number |
  |--------|
  | 1      |
  | 2      |
* And the following numbers

  | number |
  |--------|
  | 3      |
  | 4      |
* When the numbers are 'added'
* Then the result should be '3'

