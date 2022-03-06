# Playing with Characters
**Source: Hackerrank**
## Objective
The fundamental data types in c are int, float and char. Today, we're discussing int and float data types.

## Task
Your task is to take two numbers of int data type, two numbers of float data type as input and output their sum:

1. Declare 4 variables: two of type int and two of type float.
2. Read 2 lines of input from stdin (according to the sequence given in the 'Input Format' section below) and initialize your  variables.
3. Use the + and - operator to perform the following operations:
    - Print the sum and difference of two int variable on a new line.
    - Print the sum and difference of two float variable rounded to one decimal place on a new line.

## Input Format
The first line contains two integers. </br>
The second line contains two floating point numbers.

## Constraints
 1 &le; integer variables &le; 10<sup>4</sup> </br>
 1 &le; float variables &le; 10<sup>4</sup> </br>

## Output Format

rint the sum and difference of both integers separated by a space on the first line, and the sum and difference of both float (scaled to 1 decimal place) separated by a space on the second line.

## Sample Input

```
10 4
4.0 2.0
```

## Sample Output

```
14 6
6.0 2.0
```

## Solution

```C
#include <stdio.h>
int main()
{
    int a,b;
    float c,d;
    scanf("%d%d%f%f",&a,&b,&c,&d);
    printf("%d %d\n%0.1f %0.1f", a+b, a-b, c+d, c-d);
    return 0;
}
```