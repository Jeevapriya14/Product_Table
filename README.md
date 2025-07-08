# Product Table
## Date: 08/07/2025
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
```
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1" />
  <title>Product Table</title>
  <link rel="stylesheet" href="styles.css" />
</head>
<body>
  <table>
    <caption>Available Products</caption>
    <thead>
      <tr>
        <th>Product Name</th>
        <th>Product Price</th>
        <th>Description</th>
      </tr>
    </thead>
    <tbody>
      <tr>
        <td>Laptop</td>
        <td>₹45,000</td>
        <td>High-speed performance</td>
      </tr>
      <tr>
        <td>Phone</td>
        <td>$499</td>
        <td>Budget-friendly</td>
      </tr>
      <tr>
        <td>Headphones</td>
        <td>₹2,500</td>
        <td>Noise-cancelling feature</td>
      </tr>
      <tr>
        <td>Smartwatch</td>
        <td>$199</td>
        <td>Fitness tracking</td>
      </tr>
    </tbody>
  </table>
</body>
</html>

```
## CSS:
```
body {
  background-color: #f9f9f9;
  font-family: Arial, sans-serif;
  margin: 20px;
}

table {
  border-collapse: collapse;
  margin: auto;
  width: 80%;
  box-shadow: 0 0 10px rgba(0, 0, 0, 0.1);
}

caption {
  font-weight: bold;
  margin-bottom: 10px;
  font-size: 1.2em;
  text-align: center;
}

thead th {
  background-color: #4caf50;
  color: white;
  padding: 12px 15px;
  text-align: left;
}

tbody td {
  border: 1px solid #ddd;
  padding: 10px 15px;
}

tbody tr:nth-child(even) {
  background-color: #f2f2f2;
}

tbody tr:hover {
  background-color: #e0f7e9;
  cursor: pointer;
}

```
## Output:
![image](https://github.com/user-attachments/assets/dc3a3015-c1d4-4528-b773-f2779669c361)


## Result:
A structured HTML table that displays product-related information, including product names, prices, and descriptions, useful for catalogs, listings, or e-commerce prototypes is created successfully.
