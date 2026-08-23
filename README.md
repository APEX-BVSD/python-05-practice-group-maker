# Practice: Group Maker
Write a program that asks the user for a number of people and the group size. The program outputs
how many groups of that size can be made, and how many people are left over.

## Input
1. The number of people total
2. The size of the groups

## Error Checking
Your program should check that the number of people and group size are 1 or more.

## Output
This exact string "With _ people, you can make _ groups of _ with _ (person/people) leftover." Choose person/people depending on the number.

## Examples

```
Inputs
17
4

Output
With 15 people, you can make 4 groups of 4 with 1 person leftover.
```

```
Inputs
23
5

Output
With 23 people, you can make 5 groups of 4 with 3 people leftover.
```

```
Inputs
-5
5

Output
ERROR: The number of people must be 1 or more.
```

```
Inputs
10
0

Output
ERROR: The group size must be 1 or more.
```

## Testing
The autograder will run multiple cases to ensure that you have covered all of the cases.