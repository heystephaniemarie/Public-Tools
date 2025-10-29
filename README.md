# PayPal CSV Formatter

A free, browser-based tool for bookkeepers to format PayPal CSV exports for QuickBooks import.

## 🎯 What It Does

This tool automatically reformats PayPal CSV files to make them QuickBooks-ready by:

- Adding a "Vendor" column between "Time Zone" and "Description"
- Populating the Vendor field with Name (if available) or Description
- Removing all quotes from fields
- Formatting time values to remove leading zeros

## 🚀 Live Demo

[Add your Netlify URL here once deployed]

## 💻 How It Works

This is a completely client-side tool - no data is sent to any server. All processing happens in your browser using JavaScript, which means:

- ✅ Your data stays private and secure
- ✅ Works offline once loaded
- ✅ No server costs or maintenance
- ✅ Fast processing

## 🛠️ Technical Details

- Pure HTML/CSS/JavaScript - no frameworks or dependencies
- Uses custom CSV parser to handle quoted fields and edge cases
- Implements the same logic as the original Python version
- Responsive design works on desktop and mobile

## 📊 Usage

1. Visit the tool URL
2. Upload or drag-and-drop your PayPal CSV file
3. Click "Process File"
4. Preview the results
5. Download the formatted CSV file
6. Import into QuickBooks

## 🔧 Local Development

To run locally, simply open `paypal-csv-formatter.html` in your browser. No build process or dependencies required.

## 📝 Feedback

Found a bug or have a suggestion? Use the feedback form on the tool page or [create an issue](https://github.com/YOUR_USERNAME/YOUR_REPO/issues).

## 📄 License

Free to use for personal and commercial purposes.

## 🙏 Credits

Created for bookkeepers who need a simple, reliable way to format PayPal exports for QuickBooks.
