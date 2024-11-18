<!DOCTYPE html>
<html lang="en">

<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Amazon-Style Add to Cart Button</title>
  <link href="https://fonts.googleapis.com/css2?family=Roboto:wght@400;700&display=swap" rel="stylesheet">
  <style>
    body {
      font-family: 'Roboto', sans-serif;
      margin: 0;
      padding: 0;
      display: flex;
      justify-content: center;
      align-items: center;
      height: 100vh;
      background-color: #f5f5f5;
    }

    .container {
      background: white;
      border-radius: 15px;
      box-shadow: 0 4px 8px rgba(0, 0, 0, 0.1);
      max-width: 400px;
      padding: 20px;
      text-align: center;
    }

    h1 {
      font-size: 24px;
      color: #333;
      margin-bottom: 20px;
    }

    ul {
      list-style: none;
      padding: 0;
      margin: 0 0 20px 0;
      text-align: left;
    }

    ul li {
      margin: 10px 0;
      font-size: 16px;
      color: #555;
      display: flex;
      align-items: center;
    }

    ul li::before {
      content: "✔";
      color: #ffab00;
      font-size: 18px;
      margin-right: 10px;
    }

    .btn1 {
      background-color: rgb(255, 216, 20);
      padding: 12px 70px;
      border: none;
      font-family: Arial, Helvetica, sans-serif;
      font-weight: normal;
      font-size: 18px;
      border-radius: 100px;
      color: #292929;
      cursor: pointer;
      display: inline-block;
      transition: background-color 0.3s ease;
    }

    .btn1:hover {
      background-color: #dfb520;
    }
  </style>
</head>

<body>
  <div class="container">
    <h1>Amazon-Style Add to Cart Button</h1>
    <ul>
      <li><strong>Stylish Design</strong>: Rounded edges with a vibrant yellow background that enhances visibility.</li>
      <li><strong>Hover Effect</strong>: Subtle color change on hover for an interactive user experience.</li>
      <li><strong>Responsive Layout</strong>: Center-aligned button, adaptable to various screen sizes.</li>
      <li><strong>Clean Code</strong>: Easy-to-read and customizable HTML and CSS.</li>
    </ul>
    <button class="btn1">Add to Cart</button>
  </div>
</body>

</html>
