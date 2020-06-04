## Kata
![ ](kata.png)

### Stock portfolio

Implement the following user story using Outside-In TDD starting from an acceptance test.

**Portfolio User Story**

As a customer of our stock exchange broker

I would like to see my current portfolio

So I can better plan my financial strategy

*Portfolio scenario*

We need to provide a class able to record the buy and sell operations of a customer and display the information as per the acceptance criteria. For simplicity, you can assume it should work for just one user at a time.

*Print portfolio criteria*

Given I bought 1000 shares of "Old School Waterfall Software LTD" on 14/02/1990

and I bought 400 shares of "Crafter Masters Limited" on 09/06/2016

and I bought 700 shares of "XP Practitioners Incorporated" on 10/12/2018

and I sold 500 shares of "Old School Waterfall Software LTD" on 11/12/2018

and the current share value of "Old School Waterfall Software LTD" is $5.75

and the current share value of "Crafter Masters Limited" is $17.25

and the current share value of "XP Practitioners Incorporated" is $25.55
 

When I print my current portfolio


Then the outcome displayed should be:

`company | shares | current price | current value | last operation`

`Old School Waterfall Software LTD | 500 | $5.75 | $2,875.00 | sold 500 on 11/12/2018`

`Crafter Masters Limited | 400 | $17.25 | $6,900.00 | bought 400 on 09/06/2016`

`XP Practitioners Incorporated | 700 | $25.55 | $17,885.00 | bought 700 on 10/12/2018`

Sorted by first operation date ascending.
