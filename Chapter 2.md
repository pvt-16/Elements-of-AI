## Chapter 2

>*AI problem solving*

First stage of the problem solving process: defining the choices and their consequences,
Eg: Toy problem: chicken crossing
    Find independent movable objects
    Consider dependency -> List objects (both independent and dependent)
    List positions
    Find combinations of objects and positions -> States
    Eliminate impossible states
    Figure out possible state transitions
    Now that we have formulated the alternative states and transitions between them, the rest becomes a mechanical task: find path.

To formalize a planning problem, we use concepts such as the state space, transitions, and costs.

**State space**: set of possible situations. Eg: could be the set of locations defined by their (x,y) coordinates Or a constrained set of locations.

**Transitions**: possible moves between one state and another. Single actions.

**Costs**:  Some transitions more preferable or cheaper
Eg:Tower of Hanoi
