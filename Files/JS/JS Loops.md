for 
    for (iterator; condition; iteration) {
        logic;
    }

    Iterator - Variable that controls how the loop iterates or goes through the logic. 
        Ex. let i = 0;
    Condition - Tells the loop how many times it should iterate.
        Ex. i < 3; 
    Iteration - Tells the loop what to do with the iterator after each run.


for-of 
    Iterates over each item in an iterable object and temporarily assigns it to a variable.
    
    for (const x_value of x_array) {
        result = result + x_value; // Concatenation
    }

else if
    Will move to the next condition if the the previous is false.

    if (false) {
        logic;
    } else if {
        console.log("Since if statement is false, I will print this message instead!");
    }


while
    Will run over and over until the condition specified is no longer true.

    while(condition) {
        logic;
    }
