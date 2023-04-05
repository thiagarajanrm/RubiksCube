# RubiksCube
Steps to solve Rubik's cube

### L  - Left Clockwise
### L1 - Left Counter Clockwise (or Left Inverse)

### R  - Right Clockwise
### R1 - Right Counter Clockwise (or Right Inverse)

### U  - Up Clockwise
### U1 - Up Counter Clockwise (or Up Inverse)

### D  - Down Clockwise
### D1 - Down Counter Clockwise (or Down Inverse)

### B  - Bottom Clockwise
### B1 - Bottom Counter Clockwise (or Bottom Inverse)

### F  - Front Clockwise
### F1 - Front Counter Clockwise (or Front Inverse)

## Sides

### White -> Yellow
### Red -> Orange
### Green -> blue

## Alogorithm

### Step:1

#### Prerequsite
First arrange white in one side. You just need to make sure that 3 white tiles are available in one side. Make sure that the 4th white tile is just below the corner where you have different color tile. Then apply the following algorithm

## $R^1$, &nbsp;&nbsp;&nbsp; D, &nbsp;&nbsp;&nbsp; R, &nbsp;&nbsp;&nbsp; $D^1$

#### Expectation

One side should be all white

### Step:2

#### Prerequsite

White facing up

## $R^1$, &nbsp;&nbsp;&nbsp; D,&nbsp;&nbsp;&nbsp; R, &nbsp;&nbsp;&nbsp;  $L^1$, &nbsp;&nbsp;&nbsp; $D^1$, &nbsp;&nbsp;&nbsp; L, &nbsp;&nbsp;&nbsp; $R^1$, &nbsp;&nbsp;&nbsp; D, &nbsp;&nbsp;&nbsp; R

#### Expectation
All white tiles on top and 2 matching tiles on first row (4 sides).

### Step:3

#### Prerequsite
White tiles at the bottom

## R, &nbsp;&nbsp;&nbsp; U, &nbsp;&nbsp;&nbsp; $R^1$, &nbsp;&nbsp;&nbsp; U, &nbsp;&nbsp;&nbsp; R, &nbsp;&nbsp;&nbsp; Ux2, &nbsp;&nbsp;&nbsp; $R^1$

#### Expectation
All bottom tiles should be Yellow and all top tile should be White and 2 matching tiles on first row (4 sides).

### Step:4
#### Prerequsite
Yellow side facing up
Matching side should be away from you.
## $R^1$, &nbsp;&nbsp;&nbsp; F,&nbsp;&nbsp;&nbsp; $R^1$, &nbsp;&nbsp;&nbsp; $B^1$ x2, &nbsp;&nbsp;&nbsp; R, &nbsp;&nbsp;&nbsp; $F^1$, &nbsp;&nbsp;&nbsp; R, &nbsp;&nbsp;&nbsp; $B^1$ x2, &nbsp;&nbsp;&nbsp; Rx2, &nbsp;&nbsp;&nbsp; $B^1$ x2
#### Expectation
All four side should be solved
