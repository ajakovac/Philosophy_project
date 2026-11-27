
### Understanding the world

- "world": a self-contained system
- what is the world like and why is that so?
- collect information $\to$ facts, information $\to$ most important (big data, information society)
- facts without context, interpretation are useless
    - e.g.: position of an object? can not be directly accessed!
    - we can measure something, e.g. '42'
    - "position" is an abstraction, interretation that can follow from our measurements
- number of facts is infinite
    - what is important what is not?
    - collecting facts $\to$ nature
    - which facts to collect $\to$ worldview
- correct interpretation
    - we have to predict the future
    - the fewest data we need, the more efficient we are
- understanding
    - collect those facts that allow to answer *any* questions we are interested
    - relevant questions


### Modelling the world

- goal: describe time dependence
    - including artificial time dependence like a label is the "consequence" of the data
    - no explicit time dependence $\to$ introduce a variable is necessary
    - today fully determines tomorrow; what is totally forgotten, can not have effect $\to$ *Markovian*, first order recursion
- world models
    - **state** ($S$): every information that fully determines the future as a Markov process
        - we do not need *all* facts $\to$ chosen facts that carry enough information
        - to describe the state we have to choose **state variables**
        - not unique, but number of them is determined $\to$ amount of information needed to describe the world (degrees of freedom, $N_\text{dof}$)
        - all other measurements can be expressed by the state variables
    - **dynamics** ($\mathcal D$): the actual recursion $\mathcal D: S\to S$, mapping today's state to tomorrow's state

- can the world be fully understood? $\to$ need both finite number of state variables and finite dynamics
    - **mechanics** systems
        - state variables: describing matter configuration $\to$ positions and velocity of point masses
        - derived quantities: energy, momentum, acceleration
        - dynamic model: Newton equations, or Hamiltonian/Lagrangian
    - **electrodynamics**
        - state variables: vectorpotential, currents
        - dynamics: Maxwell-equations
    - **Standard Model**
        - state variables: matter and gauge fields
        - dynamics: Standard Model
- **scientific method**
    - state variables are the microscopic degrees of freedom, the others are dervied quantities
    - understand the microscopic details
        - get the correct state variables
        - find out the model
        - refine experiment-by-experiment
    - ultimate goal: TOE (Theory of Everything) $\to$ SM is a good candidate
    - all other observables are derived quantities!
    - seems to be a complete description $\to$ leads to complete understanding of the world

- how many world variables are there?
    - Occham's razor $\to$ we shall keep the fewest possible state variables



### Failiure of the scientific method


- **paradox**
    - examples:
        - granny's cake
        - eating soup
    - we can use the world (segments of the world) without knowing the TOE $\to$ without knowing the state variables, the relevant questions
    - after knowing SM (the proxy TOE), we stil do not know anything about the other segments of the world
    - concepts are too complicated from the SM point of view: not eviden, what is the difference on quark level between the cake and the granny...

- observation
    - two atom system is more complicated than a one atom system
    - three atom system is even more complicated
    - $10^{23}$ atom system, however, is simpler $\to$ gas or solid
- conclusion
    - the relevant questions change
    - what is relevant on small scale, *irrelevant* on larger scales! the state is described by completely different variables
    - what is relevant on large scales, irrelevant (or simple does not even exist) on small scales (like "granny")
- Why? How can we describe this behavior mathematically?

