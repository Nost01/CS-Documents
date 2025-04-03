let variable; 
    Can include letters, dollar signs, underscores and numbers.
    Cannot include spaces or start with a number.

let variable = "text";
let variable = 69;
let variable = [] 
    Assigning a value to a variable initializes it.

console.log(variable);
    Can print the value of a variable.
    If the variable is uninitialized (no value), console will display "undefined".

variable = "new-text"
variable = new-number;
variable = variable2;
    Can reassign a variables.



Ex. Array
    let rows = ["Digga1", "Digga2", "Digga3"]

    console.log(rows[0]); // will print "Digga1".
    
    rows[1] = "Digga22"; // Changes second index (starts at 0) to a new value
    console.log(rows); // will print ["Digga1", "Digga22", "Digga3]
    rows[rows.length]; // # of contents in array