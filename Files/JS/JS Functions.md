function new(parameter) {
    return parameter;
}

const temp_val = new("argument"); 
console.log(temp_val);
    // Call the function by attaching it to a variable. 
    // Pass an argument for the parameter part of the function call.
    // Outputs to the console.


EXAMPLE
    function addTwoNumbers(numOne, numTwo) {
        return numOne + numTwo;
    }

    const sum = addTwoNumbers(6, 9);
    console.log(sum)

    OUTPUT: 15

Notes:
    All functions return a value.
    Parameters of a function are given a value when you call the function.
    Any code after the return in a function will no execute. 