Methods
        .push() // Pushes a value to the end of an array.
        .pop() // Removes the last element of an array.
        .unshift() // Adds a value to the beginning of the array.
        .shift() // Removes the first element of an array.









Examples

1. Getting the average of numbers in an array.

function getAverage(scores) {
        let sum = 0;
        
        for (const score of scores) {
                sum += score;
        }

        return sum / scores.length;
}

console.log(getAverage([50, 50, 50]));

= 50
