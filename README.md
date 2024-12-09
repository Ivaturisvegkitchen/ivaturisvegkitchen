## Hi there 👋

<!--
**Ivaturisvegkitchen/ivaturisvegkitchen** is a ✨ _special_ ✨ repository because its `README.md` (this file) appears on your GitHub profile.

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Food Ordering</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            background-color: #f8f8f8;
            color: #333;
        }
        header {
            background-color: #ff6347;
            color: white;
            padding: 20px;
            text-align: center;
        }
        .container {
            max-width: 800px;
            margin: 20px auto;
            padding: 20px;
            background: white;
            border-radius: 8px;
            box-shadow: 0 0 10px rgba(0, 0, 0, 0.1);
        }
        h1, h2 {
            color: #ff6347;
        }
        form {
            display: flex;
            flex-direction: column;
        }
        label {
            margin-bottom: 8px;
            font-weight: bold;
        }
        input, select, textarea, button {
            margin-bottom: 15px;
            padding: 10px;
            font-size: 16px;
            border: 1px solid #ccc;
            border-radius: 4px;
        }
        button {
            background-color: #ff6347;
            color: white;
            border: none;
            cursor: pointer;
        }
        button:hover {
            background-color: #e5533d;
        }
    </style>
</head>
<body>
    <header>
        <h1>Order Your Food Online</h1>
    </header>
    <div class="container">
        <h2>Place Your Order</h2>
        <form action="/submit-order" method="POST">
            <label for="name">Name:</label>
            <input type="text" id="name" name="name" required>

            <label for="email">Email:</label>
            <input type="email" id="email" name="email" required>

            <label for="phone">Phone Number:</label>
            <input type="tel" id="phone" name="phone" required>

            <label for="address">Delivery Address:</label>
            <textarea id="address" name="address" rows="3" required></textarea>

            <label for="food">Select Your Food:</label>
            <select id="food" name="food" required>
                <option value="">-- Choose an option --</option>
                <option value="pizza">Pizza</option>
                <option value="burger">Burger</option>
                <option value="pasta">Pasta</option>
                <option value="salad">Salad</option>
            </select>

            <label for="quantity">Quantity:</label>
            <input type="number" id="quantity" name="quantity" min="1" required>

            <label for="instructions">Special Instructions:</label>
            <textarea id="instructions" name="instructions" rows="3"></textarea>

            <button type="submit">Submit Order</button>
        </form>
    </div>
</body>
</html>

