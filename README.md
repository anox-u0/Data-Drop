# DataDrop: Interactive Data Visualization Tool
Drop it Hot

DataDrop is a modern and interactive web application that allows users to effortlessly visualize their CSV data and gain AI-powered insights. With a user-friendly interface, multiple chart types, and smart data handling, DataDrop makes understanding your data a seamless experience.
## ✨ Features

    CSV Upload: Easily upload your data via intuitive drag-and-drop or file browsing.

    Intelligent Column Type Detection: Automatically identifies column data types (Number, String, Date) to guide appropriate chart selections.

    Multiple Chart Types: Visualize your data using various chart options:

        Bar Chart: Compare values across different categories.

        Line Chart: Display trends over time or continuous data.

        Pie Chart: Show proportional distribution of data.

        Scatter Plot: Visualize relationships between two numerical variables.

    Dynamic Charting: Enjoy smooth animations as charts are generated and updated.

    Contextual Column Selection: Dropdowns dynamically enable/disable options based on the required data type for the selected chart axis, preventing common plotting errors.

    Date Handling: Automatically configures Chart.js time scales when date columns are selected for relevant axes.

    Dark Mode Toggle: Switch between light and dark themes for a comfortable viewing experience, with your preference saved locally.

    AI-Powered Data Insights: Leverage the Gemini API to generate concise, actionable insights, trends, and observations about your visualized data.

    Responsive UI/UX: A clean, intuitive design that adapts well to various screen sizes, featuring custom shadows and modern UI tweaks.

## 🚀 How to Use

    Open the Application: Open the index.html file in your web browser.

    Upload Your CSV:

        Click the "Browse" button, or drag and drop your .csv file directly into the designated "Drag & Drop your CSV file here" area.

        The file name will appear once uploaded.

    Select Chart Options:

        Once your CSV is loaded, the visualization controls will appear.

        Choose a "Chart Type" (Bar, Line, Pie, or Scatter).

        Select the appropriate "X-Axis Column" and "Y-Axis Column" for Bar, Line, or Scatter charts. The dropdowns will indicate the detected data type for each column and disable incompatible options.

        For Pie charts, select a "Value Column" (numeric) and a "Label Column".

    Generate Chart: Click the "Generate Chart" button to render your data visualization.

    Get Data Insights (AI-Powered): After a chart is generated, click the "✨ Get Data Insights ✨" button to receive a summary and observations about your data from an AI model.

    Toggle Theme: Use the sun/moon icon button in the top-right corner to switch between light and dark modes.

## ⚙️ Setup & Installation

This application is a single HTML file and does not require complex installation.

    Save the Code: Copy the entire provided HTML code and save it as index.html (or any .html file) on your local machine.

    Open in Browser: Simply open the index.html file using any modern web browser (e.g., Chrome, Firefox, Edge, Safari).

No server or external dependencies (other than the CDN links which are automatically fetched) are required to run the application.
