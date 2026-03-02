# 📊 Data Visualization Tool (AngularJS)

A beautiful and interactive data visualization tool built with AngularJS (1.x), Chart.js, HTML, and CSS.

## Features

✅ **CSV File Upload** - Upload any CSV file to visualize your data  
✅ **Data Table Display** - View your data in a clean, responsive table  
✅ **Dynamic Chart Types** - Choose between Bar, Line, and Pie charts  
✅ **Axis Selection** - Select any columns for X-axis and Y-axis  
✅ **Real-time Updates** - Charts update instantly when you change selections  
✅ **Reset Functionality** - Clear all data and start fresh  
✅ **Responsive Design** - Works on desktop and mobile devices  
✅ **Beautiful UI** - Modern gradient background with clean layout  

## Technologies Used

- **AngularJS 1.8.2** - For data binding and dynamic updates
- **Chart.js 3.9.1** - For creating beautiful charts
- **HTML5** - Structure
- **CSS3** - Styling with gradients and animations
- **Vanilla JavaScript** - CSV parsing and file handling

## How to Use

1. **Open the Application**
   - Simply open `index.html` in any modern web browser
   - No server or installation required!

2. **Upload a CSV File**
   - Click the "📁 Choose CSV File" button
   - Select a CSV file from your computer
   - The data will be displayed in a table automatically

3. **Visualize Your Data**
   - Select a chart type (Bar, Line, or Pie)
   - Choose a column for the X-axis
   - Choose a column for the Y-axis
   - The chart will update automatically

4. **Reset**
   - Click the "🔄 Reset" button to clear all data and start over

## Sample Data

A sample CSV file (`sample-data.csv`) is included with product sales data. You can use this to test the application.

### CSV Format

Your CSV file should be formatted like this:

```csv
Column1,Column2,Column3
Value1,Value2,Value3
Value4,Value5,Value6
```

**Example:**
```csv
Product,Sales,Revenue
Laptop,150,75000
Phone,200,40000
Tablet,120,36000
```

## Features in Detail

### 📁 File Upload
- Accepts CSV files only
- Displays the uploaded file name
- Shows a message if no file is uploaded

### 📋 Data Table
- Displays all columns from your CSV
- Shows first 10 rows (with total count)
- Responsive and scrollable
- Hover effects on rows

### 📊 Chart Visualization
- **Bar Chart** - Compare values across categories
- **Line Chart** - Show trends over time or categories
- **Pie Chart** - Display proportions and percentages
- Automatic color coding
- Responsive and centered layout
- Handles up to 20 data points for optimal visualization

### 🎨 Design
- Modern gradient background (purple to blue)
- Clean white container with rounded corners
- Smooth animations and hover effects
- Mobile-responsive layout
- Professional typography

## Browser Compatibility

Works on all modern browsers:
- ✅ Chrome
- ✅ Firefox
- ✅ Safari
- ✅ Edge
- ✅ Opera

## Tips

1. **For best results**, use CSV files with:
   - Clear column headers in the first row
   - Numeric values for Y-axis (for meaningful charts)
   - Categorical or sequential data for X-axis

2. **Chart Types**:
   - Use **Bar charts** for comparing categories
   - Use **Line charts** for trends and time series
   - Use **Pie charts** for showing proportions (works best with fewer categories)

3. **Data Limits**:
   - The table shows the first 10 rows
   - Charts display up to 20 data points for clarity
   - All data is still processed and available

## Troubleshooting

**Chart not showing?**
- Make sure both X-axis and Y-axis columns are selected
- Ensure your Y-axis column contains numeric values

**CSV not loading?**
- Check that your file is in CSV format (comma-separated)
- Ensure the file has headers in the first row
- Make sure there are no empty lines at the start

**Data looks wrong?**
- Verify your CSV uses commas (,) as separators
- Check for any special characters in your data

## License

Free to use for personal and commercial projects.

## Credits

Created with ❤️ using AngularJS and Chart.js

---

**Enjoy visualizing your data! 📊✨**
