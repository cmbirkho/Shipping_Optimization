
#### The code in this repository is an example of a shipping optimization tool. The goal is define functions that can select the optimal shipping service based on the constraints we set. We'll use linear programming and the `lpSolveAPI` library for the optimization.

#### In this example we are simulating an ecommerce environment where orders come in to an order management system and need to be assigned a shipping service before the order drops into the distribution center's warehouse management system. We'll try to recreate that process of assigning the shipping service, but doing so in a way that optimizes business contraints (i.e. costs, customer service, etc.)
