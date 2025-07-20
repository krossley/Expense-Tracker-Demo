# 💰 Expense Tracker Demo

A modern, responsive web application for tracking personal income and expenses with interactive charts, budget management, and data export capabilities.

## 🌟 Features

### Core Functionality
- **Transaction Management**: Add, view, and delete income and expense transactions
- **Budget Tracking**: Set monthly budget limits for different expense categories
- **Data Persistence**: All data is saved locally in your browser
- **Smart Filtering**: Filter transactions by type, category, and time period

### Visual Analytics
- **Interactive Charts**: 
  - Doughnut chart showing expenses by category
  - Line chart displaying monthly income vs expenses trends
- **Real-time Dashboard**: Live updates of total income, expenses, balance, and transaction count
- **Budget Progress Bars**: Visual indicators showing spending against set budgets

### Data Management
- **Multiple Export Formats**: 
  - CSV export for spreadsheet analysis
  - JSON export for data backup
  - Text report generation with insights
- **Data Validation**: Form validation and error handling
- **Responsive Design**: Works seamlessly on desktop and mobile devices

## 🚀 Getting Started

### Prerequisites
- A modern web browser (Chrome, Firefox, Safari, Edge)
- No server or installation required!

### Installation
1. Clone this repository:
   ```bash
   git clone https://github.com/krossley/Expense-Tracker-Demo.git
   ```

2. Navigate to the project directory:
   ```bash
   cd Expense-Tracker-Demo
   ```

3. Open `index.html` in your web browser:
   - Double-click the file, or
   - Right-click and select "Open with" your preferred browser, or
   - Use a local server for development

## 📱 How to Use

### Adding Transactions
1. Fill out the "Add Transaction" form with:
   - Description (what the transaction was for)
   - Amount (positive number)
   - Type (Income or Expense)
   - Category (automatically populated based on type)
   - Date

2. Click "Add Transaction" to save

### Setting Budgets
1. Use the "Budget Management" form to:
   - Select an expense category
   - Set a monthly budget limit
   - Click "Set Budget"

2. Monitor your spending against budgets in the "Budget Overview" section

### Viewing Data
- **Dashboard**: See your financial summary at the top
- **Transactions List**: View all transactions with filtering options
- **Charts**: Analyze spending patterns and trends
- **Budget Overview**: Track progress against set limits

### Exporting Data
Choose from three export options:
- **CSV**: For use in Excel or Google Sheets
- **JSON**: For data backup or importing elsewhere
- **Report**: Human-readable summary with insights

## 🏗️ Technical Details

### Built With
- **HTML5**: Semantic markup and modern web standards
- **CSS3**: Advanced styling with grid, flexbox, and animations
- **JavaScript (ES6+)**: Modern JavaScript with local storage
- **Chart.js**: Interactive charts and data visualization

### Browser Compatibility
- Chrome 70+
- Firefox 65+
- Safari 12+
- Edge 79+

### Data Storage
- Uses browser's localStorage for data persistence
- No server required - all data stays on your device
- Data includes transactions, budgets, and user preferences

## 🎨 Design Features

### User Interface
- **Modern Design**: Clean, professional interface with gradient backgrounds
- **Responsive Layout**: Adapts to different screen sizes automatically
- **Interactive Elements**: Hover effects, smooth transitions, and animations
- **Intuitive Navigation**: Clear visual hierarchy and user-friendly forms

### Color Scheme
- Income: Green (#28a745)
- Expenses: Red (#dc3545)
- Primary: Purple gradient (#667eea to #764ba2)
- Neutral: Various grays for supporting elements

## 📊 Categories

### Income Categories
- Salary
- Freelance
- Business
- Investments
- Gifts
- Other Income

### Expense Categories
- Food & Dining
- Transportation
- Shopping
- Entertainment
- Bills & Utilities
- Healthcare
- Education
- Travel
- Other Expense

## 🔧 Development

### File Structure
```
Expense-Tracker-Demo/
├── index.html          # Main application file
└── README.md          # This file
```

### Key Functions
- `addTransaction()`: Handles new transaction creation
- `setBudget()`: Manages budget limits
- `updateCharts()`: Refreshes chart data
- `filterTransactions()`: Applies user filters
- `exportToCSV()`: Generates CSV downloads

### Local Development
The application is entirely client-side and can be developed by:
1. Opening `index.html` in a browser
2. Making changes to the code
3. Refreshing the browser to see updates

## 📈 Future Enhancements

Potential improvements could include:
- **Cloud sync**: Save data across devices
- **Advanced reporting**: More detailed analytics
- **Recurring transactions**: Automatic monthly entries
- **Category customization**: User-defined categories
- **Multi-currency support**: Handle different currencies
- **Goal setting**: Financial targets and progress tracking

## 🐛 Known Issues

- Data is stored locally only (cleared if browser data is cleared)
- Charts require internet connection for Chart.js CDN
- Large datasets may impact performance on older devices

## 🤝 Contributing

This is a demo project, but suggestions and improvements are welcome! Feel free to:
1. Fork the repository
2. Create a feature branch
3. Make your changes
4. Submit a pull request

## 📄 License

This project is open source and available under the [MIT License](LICENSE).

## 📞 Support

For questions or issues:
- Create an issue on GitHub
- Check the browser console for error messages
- Ensure JavaScript is enabled in your browser

---

**Made with ❤️ for better financial management**

*Last updated: July 2025*
