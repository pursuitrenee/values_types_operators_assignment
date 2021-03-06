V # Values, Types & Operators Exercises

1. What are the types of the following expressions and what do they evaluate to, and why?

* `17`// Number. This number evaluates to 17 because there are no operators.

* `1 + 2 * 3 + 4`// These are numbers and operators. They evaluate to 11. This is because the system evaluates  the multiplication operator first and then evaluates the addition.

* `800 / 80 / 8`// This expression contains numbers and an operator. The expression evaluates to 1.25 because 800 divided by 80 equals 10 and 10 divided by 8 equals 1 with a remainder of 2. The remainder of 2 is reprensented as the .25

* `400 > 200` // This is a Boolean expression which evaluates to true because 400 is greater than 200.

* `1 !== 1` // This is a Boolean expression with numbers and comparison operators. They evaluate to false because this operator test for inequality but these numbers are the same.

* `true || false` // This is a boolean expression which evaluates to true because of the "OR" which is the logical operator connecting both sides of the expression.

* `true && false` // This is a boolean expression which evaluates to false because of the "AND" which is the logical operator connecting both sides of the expression. The && operator will evaluate to true only if both left-hand and right-hand sides are true

* `20 % 6` // This expression contains numbers with a modular operator. It evaluates to "2" because there is a remainder of 2 when 20 is divided by 6

* `'a' + 'b'`// This expression contains 2 strings with an operator. The expression evaluates to "ab" because the "+" joins both strings together. This is known as a string concatenation.

2. What will the following return?

* `typeof 4` // Number

*  `typeof 'hello // String

*  `typeof true` // boolean

* `2 === 1 || 3 === 4` // false

3. Create a truth table for the expression A || B.
ANSWER:
|   A   |   B   | A || B |
| true  | true  | true  |
| false | true  | true  |
| true  | false | true  |
| false | false | false |


4. Create a truth table for the expression !A && !B.
ANSWER:

|   A   |   B   |   !A   |   !B   | !A && !B |
| true  | true  | false  | false  | false    |
| false | true  | true   | false  | false    |
| true  | false | false  | true   | false    |
| false | false | true   | true   | true     |

5. Write a step-by-step evaluation for the following expression (remember order of operations): `2 + 3 * 2 + 1`.
    ANSWER:
    2 + 3 * 2 + 1
    2 + 6 + 1
    8 + 1
    9

 6. Write a step-by-step evaluation for the following expression (remember order of operations): `4 / 2 + 8 / 4`.
    ANSWER:
    4 / 2 + 8 / 4
    2 + 8 / 4
    2 + 2
    4

 7. Write a step-by-step evaluation for the following expression: `'ca' + 'ter' + 'pi' + 'llar'`.
    ANSWER:
    'ca' + 'ter' + 'pi' + 'llar'
    cater + pi + llar
    caterpi + llar
    caterpillar

 8. Write a step-by-step evaluation for the following expression: `2 * 4 === 8 && 'car' + 'pool' === 'carpool'`.
    ANSWER:
    2 * 4 === 8 && 'car' + 'pool' === 'carpool'
    8 === 8 && 'car' + 'pool' === 'carpool'
    8 === 8 && 'carpool' === 'carpool'
    true
