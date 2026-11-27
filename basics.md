
### Understanding the world

- "world": a self-contained *system*
    - what is the world like and why is that so?
    - to know the world: collect information (big data, information society)
- goal: predict the future
    - including artificial time dependence like a label is the "consequence" of the data
    - no explicit time dependence $\to$ introduce a variable is necessary
    - today fully determines tomorrow; what is totally forgotten, can not have effect $\to$ *Markovian*, first order recursion
    - the fewest data we need, the more efficient we are

- world models
    - **state** ($S$): every information that fully determines the future as a Markov process
        - we do not need *all* facts $\to$ chosen facts that carry enough information
        - to represent the state we have to choose **state variables**
        - not unique, but number of them is determined $\to$ amount of information needed to describe the world (degrees of freedom, $N_\text{dof}$)
        - all other measurements can be expressed by the state variables
    - **dynamics** ($\mathcal D$): the actual recursion $\mathcal D: S\to S$, mapping today's state to tomorrow's state


- models $-$ examples from physics
    - **mechanics** systems
        - state variables: describing matter configuration $\to$ positions and velocity of point masses
        - dynamic model: Newton equations, or Hamiltonian/Lagrangian
    - **electrodynamics**
        - state variables: vectorpotential, currents
        - dynamics: Maxwell-equations
    - **large energy world**
        - state variables: matter and gauge fields
        - dynamics: Standard Model
    - all of them contain very large number (infinite number) of state variables!

- **contexts** ($\mathcal C$)
    - we do want to describe every detail!
        - too many of them
        - has no relevance for our goals!
    - let us choose a set of target variables: $q$ $\to$ context
        - can be expressed by the state variables $q(X)$
    - aligned coordinate system:  $X\to Y\times Y'$
        - if chosen wisely, $q$ just depends on one of them $q(Y)$
        - **relevant** variables: $Y$
        - **irrelevant** variables: $Y'$
    - depends on the context!

- **nested contexts** 
    - define (partial) ordering among contexts $\mathcal C\succ \mathcal C'$ $\to$ more detailed (finer) context ($\mathcal C$) can explain all the target variables of the less detailed (coarser) one ($\mathcal C'$)
    - usage: if a context seems to be very complicated because of a lot of constraints, try to understand the underlying finer one
    - examples
        - clockwork: knowing the parts and the construction rules we can understand the working of the clockwork
        - atom: knowing the ingredients and the underlying dynamics (QM) we can explain the properties of the atom

- consequence: **analytic thinking**
    - state variables are the microscopic degrees of freedom, the others are dervied quantities
    - ultimate goal: TOE (Theory of Everything) $\to$ SM is a good candidate
    - all other observables are derived quantities!
    - seems to be a complete description $\to$ leads to complete understanding of the world


- **the path integral method**
    - important observations: IR physics
    - microscopic vs macroscopic 

- how many world variables are there?
    - Occham's razor $\to$ we shall keep the fewest possible state variables

- how to find the model?
    - observation: collect a lot of facts
    - **scientific method** $\to$ the traditional way; System II.
        - modelling: choose a finite number of state variables, and try to express the dynamics as well as the other observables in a given approximation
        - give predicions, verify them with experiments
        - refine the model gradually
        - state variables and models are explicit
    - **AI method** $\to$ the new way; System I.
        - choose a large functional space for the target variables
        - fit the parameters for the best description in a training set $\to$ test is in a test set
        - variables and models are implicit
    - why we needed the AI method, once we had an old reliable method?


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

