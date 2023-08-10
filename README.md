# temp.
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Temperature Converter</title>
    <link rel="stylesheet" href="styles.css">
</head>
<body>
    <div class="converter-container">
        <h2>Temperature Converter</h2>
        <div class="input-group">
            <label for="celsius">Celsius</label>
            <input type="number" id="celsius" placeholder="Enter Celsius">
        </div>
        <div class="input-group">
            <label for="fahrenheit">Fahrenheit</label>
            <input type="number" id="fahrenheit" placeholder="Enter Fahrenheit">
        </div>
        <button onclick="convertCelsiusToFahrenheit()">Convert to Fahrenheit</button>
        <button onclick="convertFahrenheitToCelsius()">Convert to Celsius</button>
    </div>

    <script src="script.js"></script>
</body>
</html>
