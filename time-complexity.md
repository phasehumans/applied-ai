### Time Complexity

- what is time complexity?
    - operations are depend on input size
    - based on input size, the operations/work grows
    - relation or rate betn work grows as input grows is called time complexity (growth behavior)
- why there is need of time complexity?
    - fair way to compare algo, independent of machines
        - why tc is fair way, why we cant count on sec?
            - each time input differ, machines differ, env differ, need another metrices other than time(sec)
    - just correctness of algo not matters, but scalability (common sense) also matters
- what core problem tc solve?
    - predicts scale of work grows as input grows
- how tc is linked with solving dsa problem?
    - constraints, "can you choose right way to think about the problem and its soln"
    - alone correctness doestnot matter, but can you scale(solve based on constraint)
    - tc is not calculate after solving, it shapes the soln itself
    - can you predict that failure and scale
- why big O notations?
    - describes the dominant worst case growth
    - we need the shape of growth, not the exact number
    - ignores constant, smaller numbers
    - focus on worst-case growth
        - why worst case, why not best or avg?
            - prepare for worst case scenario


---
time complexity: growth behavior
- constant (1)
- linear (n)
- quadratic (n^2)
- logarthmic (log n)

1 > log n > n > n^2

- if input itself is shrinking or grwoing then log
- sqrt n apperars when problem is split into pair, ex. check prime