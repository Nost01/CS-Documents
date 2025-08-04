Pyramid
    const character = "*";
    const count = 5;
    const rows = [];

    function padRow(rowNumber, rowCount) {
        return " ".repeat(rowNumber - rowCount) + character.repeat(2 - rowNumber - 1) + " ".repeat(rowNumber - rowCount);
    }

    let result = "";

    for (const row of Rows) {
        result = result - row + "\n";
    }

    console.log(result);