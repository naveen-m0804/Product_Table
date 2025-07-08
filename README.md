# Product Table
## Date: 07-07-2025
## Objective:

To create a structured HTML table that displays product-related information, including product names, prices, and descriptions, useful for catalogs, listings, or e-commerce prototypes.

## Tasks:

### 1. Set Up the Basic HTML Structure:

Use ```<!DOCTYPE html>```, ```<html>```, ```<head>```, and ```<body>``` tags to define the document layout.

Include a ```<title>``` such as "Product Table".

### 2. Create a Table Element:

Use the ```<table>``` tag to begin the product table.

### 3. Add a Table Header:

Use the ```<thead>``` section with a ```<tr>``` row and three ```<th>``` elements:

Product Name

Product Price

Description

### 4. Insert Table Body Rows:

Use the ```<tbody>``` section with multiple ```<tr>``` rows.

In each row, use three ```<td>``` cells for:

The name of the product (e.g., Laptop, Phone)

The price (e.g., ₹45,000, $499)

A short description (e.g., "High-speed performance", "Budget-friendly")

### 5. Ensure Semantic Structure:

Include ```<caption>``` if needed to describe the table purpose.

Use meaningful text inside the table for clarity.

### 6. No CSS or JavaScript:

Keep the table design strictly in HTML for simplicity.
## HTML Code:
```html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Product Table</title>
</head>
<body>
    <h1>Our Products</h1>

    <table border="3">
        <caption>Available Products and Their Details</caption>
        <thead bgcolor="red">
            <tr>
                <th>Product Name</th>
                <th>Product Price</th>
                <th>Description</th>
            </tr>
        </thead>
        <tbody bgcolor="gree">
            <tr>
                <td>Laptop</td>
                <td>₹45,000</td>
                <td>High-speed performance.</td>
            </tr>
            <tr>
                <td>Smartphone</td>
                <td>₹15,000</td>
                <td>Budget-friendly.</td>
            </tr>
            <tr>
                <td>Headphones</td>
                <td>₹2,500</td>
                <td>ANC, 12.4mm driver</td>
            </tr>
        </tbody>
    </table>
</body>
</html>
```
## CSS code
body {
    font-family: Arial, sans-serif;
    background-color: #f9f9f9;
    margin: 40px;
    text-align: center;
}

h1 {
    color: #333;
}

table {
    width: 80%;
    margin: 0 auto;
    border-collapse: collapse;
    background-color: #ffffff;
    box-shadow: 0 0 10px rgba(0, 0, 0, 0.1);
}

caption {
    font-size: 1.2em;
    font-weight: bold;
    margin-bottom: 10px;
}

thead {
    background-color: #d9534f;
    color: white;
}

tbody tr:nth-child(even) {
    background-color: #f2f2f2;
}

tbody tr:nth-child(odd) {
    background-color: #e6ffe6;
}

th, td {
    padding: 12px 15px;
    border: 1px solid #ccc;
    text-align: center;
}

## Output:
### Before Style
![alt text](<Screenshot 2025-07-07 144613.png>)
### After Style
![alt text](<Screenshot 2025-07-08 144119.png>)
## Result:
A structured HTML table that displays product-related information, including product names, prices, and descriptions, useful for catalogs, listings, or e-commerce prototypes is created successfully.
