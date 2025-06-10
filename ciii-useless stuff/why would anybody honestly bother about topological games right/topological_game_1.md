# Game Overview

  

Fixed Point Hunt is a mathematical game based on the concept of fixed points in continuous functions. In topology, a fixed point of a function $f: X \rightarrow X$ is a point $x \in X$ such that $f(x) = x$.

This pen-and-paper game challenges players to create and identify fixed points in continuous functions, making abstract mathematical concepts tangible and visual.
## Game Setup
### Player 1

**Goal**: Draw functions with exactly ONE fixed point
### Player 2

**Goal**: Draw functions with MULTIPLE fixed points
### Game Rules

- Players alternate drawing continuous functions from the region to itself

- Score 1 point each time you meet your fixed point goal

- The player with the most points after an agreed number of rounds wins
## Function Types
### Single Fixed Point Functions (Player 1)

- **Rotation around a center point**:

  $f(x,y) = (c_x + \cos\theta(x-c_x) - \sin\theta(y-c_y), c_y + \sin\theta(x-c_x) + \cos\theta(y-c_y))$

- **Contraction toward a point** $(p_x, p_y)$:

  $f(x,y) = (\alpha x + (1-\alpha)p_x, \alpha y + (1-\alpha)p_y)$ where $0 < \alpha < 1$

- **Reflection through a point** $(c_x, c_y)$:

  $f(x,y) = (2c_x - x, 2c_y - y)$
### Multiple Fixed Points Functions (Player 2)

- **Reflection across a line**:

  - Vertical line at $x = a$: $f(x,y) = (2a - x, y)$

  - Horizontal line at $y = b$: $f(x,y) = (x, 2b - y)$

- **Identity function** (all points are fixed):

  $f(x,y) = (x, y)$

- **Projection onto a region**:

  $f(x,y) = (\max(\min(x, b), a), y)$ for vertical strip $a \leq x \leq b$
### Invalid Move Example

- **Translation** (no fixed points):

  $f(x,y) = (x + a, y + b)$ where $a$ and $b$ are not both zero
## Mathematical Foundation

A key principle underlying this game is **Brouwer's Fixed-Point Theorem**, which states that any continuous function from a convex compact subset of Euclidean space to itself has at least one fixed point.
## Tips for Play

1. Draw arrows showing where key points map to

2. Identify fixed points where arrows would have zero length

3. Verify your fixed points by checking how nearby points behave