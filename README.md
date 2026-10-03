# Electronics Items Table

This project demonstrates how to create and style an **Electronics Items table** using HTML and CSS.

## 📌 Project Overview

The webpage displays a list of electronic products along with:

* Serial Number
* Product Name
* Quantity
* Per Unit Price
* Total Amount

The table also includes a **Total** row at the bottom.

## 🛠️ Technologies Used

* **HTML5** – Used to create the webpage structure and table.
* **CSS3** – Used to style the table and add hover effects.

## ✨ Features

* Centered electronics items table.
* Table width and height are defined using CSS.
* Borders are applied to the table.
* Header row has a **blue background** with **white text**.
* Rows change to **dark grey** when the mouse hovers over them.
* The final row displays the **total amount**.
* Text inside the table is center-aligned.
* `border-collapse` is used for a clean table layout.

## 📊 Table Details

| Sr. No. | Product Name | Quantity | Per Unit Price |     Amount |
| ------: | ------------ | -------: | -------------: | ---------: |
|       1 | Television   |       48 |        ₹30,000 | ₹14,60,000 |
|       2 | Laptop       |       24 |        ₹70,000 | ₹16,80,000 |
|       3 | Mobile       |       25 |        ₹50,000 | ₹12,50,000 |
|       4 | Tablet       |       23 |        ₹30,000 |  ₹6,90,000 |
|       5 | PS5 Ultimate |       25 |        ₹70,000 | ₹17,50,000 |
|       6 | AC           |       10 |        ₹60,000 |  ₹6,00,000 |
|       7 | Sound System |       15 |        ₹10,000 |  ₹1,50,000 |
|       8 | Dyson        |       23 |        ₹50,000 | ₹11,50,000 |
|       9 | Fridge       |        3 |      ₹3,00,000 |  ₹9,00,000 |
|      10 | Inverter     |        6 |        ₹40,000 |  ₹2,40,000 |

## 🎨 CSS Styling

### Table

```css
table {
    border-collapse: collapse;
    margin: auto;
    height: 500px;
    width: 500px;
    border: 2px solid black;
    text-align: center;
}
```

### Table Header

```css
th {
    background-color: blue;
    color: white;
}
```

### Hover Effect

```css
tr:hover {
    background-color: darkgrey;
}
```

When the user moves the mouse over any table row, its background color changes to dark grey.

## 📁 Project Structure

```text
Electronics-Table/
│
├── index.html
└── README.md
```

## 🚀 How to Run

1. Create a folder named `Electronics-Table`.
2. Save the HTML code as `index.html`.
3. Save this documentation as `README.md`.
4. Open `index.html` in any web browser.
5. Move the mouse over the table rows to see the hover effect.

## 🎯 Learning Objectives

This project helps beginners understand:

* HTML table creation
* `<table>`, `<tr>`, `<th>`, and `<td>` tags
* CSS table styling
* Borders and `border-collapse`
* `margin: auto`
* Table hover effects using `:hover`
* Combining HTML and CSS

## 👨‍💻 Author

Created as an HTML & CSS practice project.
