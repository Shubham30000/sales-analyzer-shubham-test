# Sales Analyzer

## 🚀 Live Demo

Experience the live application here: [https://Shubham30000.github.io/sales-analyzer-shubham-test/](https://Shubham30000.github.io/sales-analyzer-shubham-test/)

## 📋 Overview

This project is a lightweight web application designed to process and display sales data. It reads financial information from a `data.csv` file, calculates the total sum of the sales figures, and dynamically renders the aggregate total on a visually appealing webpage built with Tailwind CSS. It provides a quick and efficient way to summarize sales data at a glance.

## ✨ Features

*   **CSV Data Ingestion**: Reads and processes numerical data directly from a `data.csv` file.
*   **Total Sum Calculation**: Automatically calculates the sum of all relevant figures within the CSV.
*   **Dynamic Display**: Presents the calculated total sum prominently on the webpage.
*   **Modern UI**: Utilizes Tailwind CSS for a clean, responsive, and maintainable user interface.
*   **Client-Side Processing**: All data processing is handled within the browser for quick feedback.

## 🛠️ Technologies Used

*   **HTML5**: For structuring the content of the webpage.
*   **Tailwind CSS**: A utility-first CSS framework for rapid UI development and styling.
*   **JavaScript**: Powers the data reading, calculation, and dynamic content updates.

## 📦 Setup

To run this project locally, follow these steps:

1.  **Clone the Repository**:
    ```bash
    git clone https://github.com/Shubham30000/sales-analyzer-shubham-test.git
    ```

2.  **Navigate to the Project Directory**:
    ```bash
    cd sales-analyzer-shubham-test
    ```

3.  **Open the Application**:
    Simply open the `index.html` file in your preferred web browser. No server setup is required.
    ```bash
    open index.html
    ```
    (or `start index.html` on Windows, or double-click the file in your file explorer)

## 💡 Usage

1.  **Access the Application**: Open the `index.html` file in your web browser (or visit the [live demo](https://Shubham30000.github.io/sales-analyzer-shubham-test/)).
2.  **View Total Cost**: The webpage will automatically read `data.csv`, calculate the total sum, and display it within the `<span id='total-cost'></span>` element.
3.  **Update Data**: To update the displayed total, modify the `data.csv` file with new numerical data. Refresh the `index.html` page in your browser to see the updated sum.

## 📁 Project Structure

```
sales-analyzer-shubham-test/
├── index.html         # Main application page, includes UI and JavaScript logic
└── data.csv           # Source data file containing sales figures
```

## 📄 License

This project is licensed under the MIT License - see the [LICENSE](https://github.com/Shubham30000/sales-analyzer-shubham-test/blob/main/LICENSE) file for details.