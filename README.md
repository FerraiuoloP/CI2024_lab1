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
The algorithm uses **hill climbing** gives priority to improving the current solution, accepts worse solutions (**simulated annealing**) as temperature increases. With some probability accepts (intermediate) non-covering solutions.

# Contributors
Some techniques implemented in my proposal were discussed and developed jointly with my colleague [GDennis01](https://github.com/GDennis01/).
We started from the same template, then we discussed how simulated annealing would work in our scenario and we sort of implemented it together (although our versions differ).
