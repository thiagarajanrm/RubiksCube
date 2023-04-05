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

R$^1$, D, R, $D^1$

# 2
$R^1$, D, R, $D^1$
R1, D, R, L1, D1, L, R1, D, R

# 3
$R^1$, D, R, $D^1$
R, U, R1, U, R, Ux2, R1

# 4
$R^1$, D, R, $D^1$
$R1$ F, $R1$, B$1$x2, R, F1, R, B1x2, Rx2, B1x2
