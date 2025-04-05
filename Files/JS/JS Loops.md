for loops
    for (iterator; condition; iteration) {
        logic;
    }

    Iterator - Variable that controls how the loop iterates or goes through the logic. 
        Ex. let i = 0;
    Condition - Tells the loop how many times it should iterate.
        Ex. i < 3; 
    Iteration - Tells the loop what to do with the iterator after each run.


for-of loops - Iterates over each item in an iterable object and temporarily assigns it to a variable.
    for (const x_value of x_array) {
        result = result + x_value; // Concatenation
    }