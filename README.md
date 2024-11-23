<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>GitHub Contributions</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            background-color: #f5f5f5;
        }
        header {
            background-color: #24292f;
            color: white;
            padding: 10px 20px;
            text-align: center;
        }
        .contribution-container {
            display: flex;
            justify-content: center;
            align-items: center;
            padding: 20px;
        }
        .contribution-graph {
            background-color: #e1e4e8;
            display: grid;
            grid-template-columns: repeat(7, 1fr);
            gap: 2px;
            padding: 5px;
            max-width: 300px;
            border-radius: 8px;
        }
        .day {
            width: 30px;
            height: 30px;
            background-color: #d0d7de;
            border-radius: 4px;
        }
        .day.active {
            background-color: #28a745;
        }
        .day.inactive {
            background-color: #6a737d;
        }
        footer {
            text-align: center;
            padding: 10px;
            background-color: #24292f;
            color: white;
            margin-top: 20px;
        }
    </style>
</head>
<body>

    <header>
        <h1>GitHub Contributions</h1>
        <p>Visualize your GitHub contributions</p>
    </header>

    <div class="contribution-container">
        <div class="contribution-graph">
            <!-- Placeholder for GitHub contribution days -->
            <div class="day active"></div>
            <div class="day inactive"></div>
            <div class="day active"></div>
            <div class="day inactive"></div>
            <div class="day active"></div>
            <div class="day inactive"></div>
            <div class="day active"></div>
            <!-- Repeat as needed to represent more days -->
        </div>
    </div>

    <footer>
        <p>Created by Manish Pandey</p>
    </footer>

</body>
</html>
