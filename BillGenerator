Image to Code
Toggle Sidebar
MODELS
Toggle theme

New

Features
Generating:

HTML + Tailwind
Include screenshot of current version?


Select and update




Versions
Imported from code
v1
Toggle
Create application for invoice generator and export pdf and excel
v2
Toggle
html
Edit
Copy code
<html>
<head>
    <title>Invoice Generator</title>
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/5.15.3/css/all.min.css">
    <link href="https://fonts.googleapis.com/css2?family=Roboto:wght@400;700&display=swap" rel="stylesheet">
    <style>
        body {
            font-family: 'Roboto', sans-serif;
            background-color: #f4f4f4;
            margin: 0;
            padding: 0;
        }
        .container {
            width: 80%;
            margin: 0 auto;
            padding: 20px;
            background-color: #fff;
            box-shadow: 0 0 10px rgba(0, 0, 0, 0.1);
            margin-top: 50px;
        }
        h1 {
            text-align: center;
            margin-bottom: 20px;
        }
        .form-group {
            margin-bottom: 15px;
        }
        .form-group label {
            display: block;
            margin-bottom: 5px;
        }
        .form-group input, .form-group select, .form-group textarea {
            width: 100%;
            padding: 10px;
            box-sizing: border-box;
        }
        .form-group textarea {
            resize: vertical;
        }
        .items-table {
            width: 100%;
            border-collapse: collapse;
            margin-top: 20px;
        }
        .items-table th, .items-table td {
            border: 1px solid #ddd;
            padding: 10px;
            text-align: left;
        }
        .items-table th {
            background-color: #f4f4f4;
        }
        .add-item-btn {
            display: inline-block;
            margin-top: 10px;
            padding: 10px 20px;
            background-color: #28a745;
            color: #fff;
            text-decoration: none;
            border-radius: 5px;
        }
        .add-item-btn:hover {
            background-color: #218838;
        }
        .generate-btns {
            text-align: center;
            margin-top: 20px;
        }
        .generate-btns button {
            padding: 10px 20px;
            margin: 5px;
            border: none;
            border-radius: 5px;
            cursor: pointer;
        }
        .generate-btns .pdf-btn {
            background-color: #dc3545;
            color: #fff;
        }
        .generate-btns .excel-btn {
            background-color: #007bff;
            color: #fff;
        }
        .generate-btns .pdf-btn:hover {
            background-color: #c82333;
        }
        .generate-btns .excel-btn:hover {
            background-color: #0056b3;
        }
    </style>
</head>
<body>
    <div class="container">
        <h1>Invoice Generator</h1>
        <div class="form-group">
            <label for="invoice-number">Invoice Number</label>
            <input type="text" id="invoice-number" placeholder="Enter invoice number">
        </div>
        <div class="form-group">
            <label for="invoice-date">Invoice Date</label>
            <input type="date" id="invoice-date">
        </div>
        <div class="form-group">
            <label for="client-name">Client Name</label>
            <input type="text" id="client-name" placeholder="Enter client name">
        </div>
        <div class="form-group">
            <label for="client-address">Client Address</label>
            <textarea id="client-address" rows="4" placeholder="Enter client address"></textarea>
        </div>
        <table class="items-table">
            <thead>
                <tr>
                    <th>Item Description</th>
                    <th>Quantity</th>
                    <th>Unit Price</th>
                    <th>Total</th>
                </tr>
            </thead>
            <tbody id="items-body">
                <tr>
                    <td><input type="text" placeholder="Enter item description"></td>
                    <td><input type="number" placeholder="Enter quantity"></td>
                    <td><input type="number" placeholder="Enter unit price"></td>
                    <td><input type="number" placeholder="Total" readonly></td>
                </tr>
            </tbody>
        </table>
        <a href="#" class="add-item-btn" onclick="addItem()">Add Item</a>
        <div class="generate-btns">
            <button class="pdf-btn" onclick="generatePDF()">Generate PDF</button>
            <button class="excel-btn" onclick="generateExcel()">Generate Excel</button>
        </div>
    </div>

    <script>
        function addItem() {
            const tableBody = document.getElementById('items-body');
            const newRow = document.createElement('tr');
            newRow.innerHTML = `
                <td><input type="text" placeholder="Enter item description"></td>
                <td><input type="number" placeholder="Enter quantity"></td>
                <td><input type="number" placeholder="Enter unit price"></td>
                <td><input type="number" placeholder="Total" readonly></td>
            `;
            tableBody.appendChild(newRow);
        }

        function generatePDF() {
            // Implement PDF generation logic here
            alert('PDF generation is not implemented yet.');
        }

        function generateExcel() {
            // Implement Excel generation logic here
            alert('Excel generation is not implemented yet.');
        }
    </script>
</body>
</html>
Message Blackbox or upload image...

Upload Files
By using Blackbox you agree to the Terms and Privacy.
