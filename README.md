# Table Multi-format Editor & Converter

A powerful, responsive web application for creating, editing, and converting table data between multiple formats: **Markdown**, **CSV**, **JSON**, and **HTML**. Edit in any format and see all others update automatically in real-time.

## 🚀 Features

### **Multi-format Support**

- **Markdown**: Standard table format with pipes and dashes (used in ChatGPT and GitHub)
- **CSV**: Comma-separated values for spreadsheet import/export
- **JSON**: Lossless array-of-arrays format for RESTful APIs (not objects for 100% data compatibility)
- **HTML**: Clean table code for web pages with beautified display

### **Real-time Conversion**

- Bidirectional conversion between all formats
- Edit in any format - all others update instantly
- Smart parsing that handles edge cases and special characters
- Preserves data integrity across all conversions

### **User Experience**

- **Click-to-Edit**: Click any section to edit directly in that format
- **Live Preview**: See your table rendered as it would appear on a website
- **Copy Functionality**: Copy any format to clipboard with dedicated copy icons
- **Collapsible Sections**: Hide/show sections to focus on specific formats
- **Responsive Design**: Works seamlessly on desktop and mobile devices

### **Advanced Features**

- **HTML Beautification**: HTML displays with proper indentation when viewing, compact when editing
- **Smart CSV Handling**: Properly escapes commas, quotes, and newlines in CSV data
- **Duplicate Column Support**: JSON format handles duplicate column names without data loss
- **Context-Aware Copying**: Copy buttons provide format-appropriate content

## 📋 Quick Start

1. **Open** `md2csv.html` in any modern web browser
2. **Choose your format**: Click any section to start editing in your preferred format
3. **Edit**: Type or paste your table data
4. **Convert**: All other formats update automatically
5. **Copy**: Use copy icons to export data in any format

## 💡 Usage Examples

### CSV Input

```csv
Name,Age,City
John,25,NYC
Jane,30,LA
```

### Markdown Input

```markdown
| Name | Age | City |
|------|-----|------|
| John | 25  | NYC  |
| Jane | 30  | LA   |
```

### JSON Input

```json
[
  ["Name", "Age", "City"],
  ["John", "25", "NYC"],
  ["Jane", "30", "LA"]
]
```

### HTML Output

```html
<table>
  <thead>
    <tr>
      <th>Name</th>
      <th>Age</th>
      <th>City</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td>John</td>
      <td>25</td>
      <td>NYC</td>
    </tr>
    <tr>
      <td>Jane</td>
      <td>30</td>
      <td>LA</td>
    </tr>
  </tbody>
</table>
```

## 🎯 Use Cases

- **Data Migration**: Convert tables between different systems and formats
- **Documentation**: Create tables in markdown for GitHub, then export to HTML for websites
- **API Development**: Convert CSV data to JSON for RESTful APIs
- **Spreadsheet Integration**: Import/export data between applications and spreadsheets
- **Content Creation**: Create tables in any format and convert as needed
- **Data Analysis**: Work with data in your preferred format while maintaining compatibility

## 🛠️ Technical Details

### **Architecture**

- **Single File**: Complete application in one HTML file
- **No Dependencies**: Pure HTML, CSS, and JavaScript
- **Client-Side**: All processing happens in the browser
- **Responsive**: CSS Grid and Flexbox for optimal layout

### **Data Processing**

- **Smart Parsing**: Handles malformed input gracefully
- **Character Escaping**: Properly handles special characters in all formats
- **Validation**: Ensures data integrity across conversions
- **Error Handling**: Graceful fallbacks for invalid input

### **Performance**

- **Real-time Updates**: Instant conversion as you type
- **Efficient Rendering**: Optimized DOM updates
- **Memory Efficient**: Minimal memory footprint
- **Fast Loading**: Single file loads instantly

## 📱 Browser Compatibility

- **Chrome**: Full support
- **Firefox**: Full support
- **Safari**: Full support
- **Edge**: Full support
- **Mobile Browsers**: Full responsive support

## 🔧 Installation

1. **Download**: Save `md2csv.html` to your local machine
2. **Open**: Double-click the file or open in your web browser
3. **Use**: No installation or setup required

## 📄 License

This project is open source and available under the MIT License.

## 🤝 Contributing

Contributions are welcome! Please feel free to submit issues, feature requests, or pull requests.

## 📞 Support

For questions, issues, or feature requests, please open an issue on GitHub.

---

**Table Multi-format Editor & Converter** - The universal tool for table data conversion and editing.
