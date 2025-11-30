CSV Data Sum Calculator

This simple web application reads numerical data from a `data.csv` file, calculates the sum of a designated column (or the first column if no header is present), and displays the total on the webpage.

## Features

- Reads `data.csv` from the same directory.
- Automatically identifies header rows and attempts to find 'amount', 'cost', or 'value' columns.
- Falls back to summing the first column if no suitable header is found or specified.
- Displays the total sum.

## Setup

1.  **Create `data.csv`**: In the same directory as `index.html`, create a file named `data.csv`. This file should contain numerical data. Example `data.csv` content:

    ```csv
    Item,Amount,Quantity
    Apple,100,5
    Banana,150,3
    Orange,75,8
    Mango,200,2
    ```

    Or simply:

    ```csv
    100
    150
    75
    200
    ```

2.  **Open `index.html`**: Open the `index.html` file in your web browser. The application will automatically fetch and process `data.csv`.

## Technologies Used

-   HTML5
-   Tailwind CSS (for styling)
-   JavaScript (ES6+ for data processing)
