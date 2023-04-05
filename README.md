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

#### Prerequsite
First arrange white in one side. You just need to make sure that 3 white tiles are available in one side. Make sure that the 4th white tile is just below the corner where you have different color tile. Then apply the following algorithm

# 1

$R$^1$, D, R, $D^1$

# 2
$R^1$, D, R, $L^1$, $D^1$, L, $R^1$, D, R

# 3
R, U, $R^1$, U, R, Ux2, $R^1$

# 4
$R^1$, F, $R^1$, $B^1$x2, R, $F^1$, R, $B^1$x2, Rx2, $B^1$x2
