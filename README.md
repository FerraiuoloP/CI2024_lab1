# CI2024_lab1
Given a family of sets, find the subfamily of minimum cost that covers all elements in the universe.\
Solve efficiently these instances customizing a technique discussed in class

| Instance | Universe size | Num sets | Density |
|----------|---------------|----------|---------|
| 1        | 100           | 10       | 0.2     |
| 2        | 1,000         | 100      | 0.2     |
| 3        | 10,000        | 1,000    | 0.2     |
| 4        | 100,000       | 10,000   | 0.1     |
| 5        | 100,000       | 10,000   | 0.2     |
| 6        | 100,000       | 10,000   | 0.3     |

# Description 
The algorithm based on **hill climbing** gives priority to improving the current solution, accepts worse solutions (**simulated annealing**) as temperature increases. With some probability accepts (intermediate) non-covering solutions.
# Run
To run in a virtual environment follow the istructions [here](https://github.com/squillero/computational-intelligence/tree/master/2024-25/contrib/poetry_installation_guide) (skipping the creation of .toml and .ipynb files)
# Contributors
Some techniques implemented in my proposal were discussed and developed jointly with my colleagues [GDennis01](https://github.com/GDennis01/) and [XhoanaShkajoti](https://github.com/XhoanaShkajoti) (on different occasions)\
We started from the same template, then we discussed how simulated annealing would work in our scenario and we sort of implemented it together (although our versions differ).
