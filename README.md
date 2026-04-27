# DataTables Sample Project

A simple employee directory application demonstrating DataTables functionality with sample data.

## Features

- **Search**: Real-time search across all columns
- **Sorting**: Click column headers to sort
- **Pagination**: Navigate through pages of data
- **Export**: Export data to CSV, Excel, PDF, or print
- **Responsive Design**: Clean, professional interface

## Sample Data

The table includes 15 sample employee records with:
- Employee ID
- Name
- Position
- Department
- Location
- Salary
- Start Date

## How to Run

Simply open `index.html` in any modern web browser. No server or build process required.

```bash
open index.html
```

Or use a local development server:

```bash
# Using Python
python -m http.server 8000

# Using Node.js
npx serve
```

Then navigate to `http://localhost:8000`

## Technologies Used

- [DataTables](https://datatables.net/) v1.13.7
- jQuery 3.7.0
- DataTables Buttons extension
- Export libraries (JSZip, pdfMake)

## Customization

You can easily customize the DataTable by modifying the initialization options in the `<script>` section:

```javascript
$('#employeeTable').DataTable({
    pageLength: 10,        // Number of rows per page
    order: [[0, 'asc']],   // Default sort column
    // Add more options here
});
```

## License

Free to use and modify for any purpose.
