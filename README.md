# Analysis on Kaprekar Routine

### By: Avery Vallee-Vezina

## What is Kaprekar Routine:

<em>Source: https://en.wikipedia.org/wiki/Kaprekar%27s_routine</em>

From Wikipedia, the free encyclopedia
"Kaprekar's constant" redirects here; not to be confused with Kaprekar number.

In number theory, Kaprekar’s routine is an iterative algorithm named after its inventor, Indian mathematician D. R. Kaprekar.[1][2] Each iteration starts with a four-digit random number, sorts the digits into descending and ascending order, and calculates the difference between the two new numbers.

As an example, starting with the number 8991 in base 10:

    9981 – 1899 = 8082
    8820 – 288 = 8532
    8532 – 2358 = 6174
    7641 – 1467 = 6174

6174, known as Kaprekar’s constant, is a fixed point of this algorithm. Any four-digit number (in base 10) with at least two distinct digits will reach 6174 within seven iterations. The algorithm runs on any natural number in any given number base. 

## What is the objective of the analysis:

Considering how most 4 digit numbers revert to 6174, the analysis will investigate if other numbers outside the range of the 4 digit numbers have their own constant when applying the Kaprekar Routine.

The steps to perform the investigation:

    Step 1 - Create a computational simulation of the Kaprekar's Routine for numbers 1000-9999
    Step 2 - Perform data analysis of Kaprekar Routine for digits 100 - 999 and 10000 - 99999 for any apparent constants
    Step 3 - Repeat previous step but for number in a different base value.

## Why this analysis is being done?:

I read about the algorithm and it sounded interesting. Then I had several questions I wished to discover on my own.