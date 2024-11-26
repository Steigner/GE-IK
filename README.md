# GE-IK

IK_1.ipynb - A simple IK solver using the PSO algorithm, demonstrating which tools we can use or compare with results from Grammatical Evolution

Fitness function: I suggest using the Euclidean distance for the first tests, and we will be using x,y,z coordinates

Grammar i guess?

```
<expression> ::= <angle>, <angle>, <angle>, <angle>, <angle>, <angle>

<angle> ::= <number>

<number> ::= -3.14 | -1.57 | -0.78 | 0 | 0.78 | 1.57 | 3.14
```

Note: number should have much bigger range

Note: Jmmc
And I have more doubts friend, it would be an equation that tries to model the 6 angles or it would be an equation for each angle friend.
For example:

An example of your data set could be:
```x ,y ,z, r, p, ,y, ang_1, ang_2 , ang_3, ang_4, ang_5, ang_6```

or for example this case which would be an equation by angle
```x ,y ,z, r, p, ,y, ang_1```
