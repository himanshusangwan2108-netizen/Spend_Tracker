# 💰 Spend Tracker

> A simple and effective tool to seamlessly track your expenses and manage your personal finances online.

[![Made with HTML](https://img.shields.io/badge/Made%20with-HTML-E34F26?style=flat&logo=html5)](https://developer.mozilla.org/en-US/docs/Web/HTML)
[![Made with CSS](https://img.shields.io/badge/Made%20with-CSS-1572B6?style=flat&logo=css3)](https://developer.mozilla.org/en-US/docs/Web/CSS)
[![Made with JavaScript](https://img.shields.io/badge/Made%20with-JavaScript-F7DF1E?style=flat&logo=javascript)](https://developer.mozilla.org/en-US/docs/Web/JavaScript)
[![License](https://img.shields.io/badge/License-MIT-green.svg)](LICENSE)

---

## 📋 Table of Contents

- [Features](#-features)
- [Getting Started](#-getting-started)
- [Usage](#-usage)
- [Customization](#-customization)
- [Technologies Used](#-technologies-used)
---

## ✨ Features

### 💸 Expense Management
- **Add Expenses**: Effortlessly log day-to-day expenses with details such as amount, category, and notes
- **Edit Expenses**: Modify existing entries to keep your records accurate
- **Delete Expenses**: Remove unwanted transactions with a single click

### 📊 Organization & Insights
- **Expense Categorization**: Organize transactions by category (food, travel, shopping, etc.)
- **Monthly Summaries**: Visualize your spending patterns with monthly breakdowns
- **Category-wise Analysis**: See exactly where your money goes with category summaries
- **Budget Management**: Set budget goals and track your progress

### 🎨 User Experience
- **User-friendly Interface**: Clean, responsive design that works on desktop and mobile
- **Data Privacy**: All information stays on your device (no external hosting)
- **Instant Updates**: Real-time tracking with no delays
- **Local Storage**: Your data persists between sessions

---

## 🚀 Getting Started

### Prerequisites

- A modern web browser (Chrome, Firefox, Safari, Edge)
- No server or installation required!

### Installation

1. **Clone the repository**
   ```bash
   git clone https://github.com/himanshusangwan2108-netizen/Spend_Tracker.git
   ```

2. **Navigate to the project directory**
   ```bash
   cd Spend_Tracker
   ```

3. **Open the application**
   ```bash
   # Simply open index.html in your browser
   # On macOS:
   open index.html
   
   # On Linux:
   xdg-open index.html
   
   # On Windows:
   start index.html
   ```

That's it! No build process, no dependencies to install. 🎉

---

## 📖 Usage

### Adding an Expense

1. Fill in the expense details in the form:
   - **Amount**: Enter the expense amount
   - **Category**: Select a category (Food, Transport, Shopping, etc.)
   - **Date**: Choose the transaction date
   - **Notes**: Add optional description

2. Click the "Add Expense" button

3. Your expense will appear in the expenses table

### Viewing Expenses

- All expenses are displayed in a sortable table
- Filter expenses by category or date range
- View monthly and category summaries

### Editing an Expense

1. Click the "Edit" button next to any expense
2. Modify the details in the form
3. Click "Update" to save changes

### Deleting an Expense

- Click the "Delete" button next to any expense
- Confirm the deletion when prompted

### Setting a Budget

1. Navigate to the Budget section
2. Set your monthly budget limit
3. Track your spending against the budget
4. Receive visual indicators when approaching the limit

---

## 🎨 Customization

### Adding New Categories

Edit the category dropdown in `index.html`:

```html
<select id="category">
  <option value="food">Food</option>
  <option value="transport">Transport</option>
  <option value="entertainment">Entertainment</option>
  <option value="your-category">Your Category</option>
</select>
```

### Changing Colors

Modify the color scheme in `css/style.css`:

```css
:root {
  --primary-color: #4CAF50;
  --secondary-color: #FFC107;
  --danger-color: #F44336;
}
```

### Adding Charts

Integrate Chart.js for visualizations:

```html
<script src="https://cdn.jsdelivr.net/npm/chart.js"></script>
```

Then create charts in your JavaScript:

```javascript
const ctx = document.getElementById('myChart').getContext('2d');
const myChart = new Chart(ctx, {
  type: 'pie',
  data: { /* your data */ }
});
```

---

## 🛠️ Technologies Used

- **HTML5** - Structure and content
- **CSS3** - Styling and animations
- **JavaScript (ES6+)** - Application logic
- **Local Storage API** - Data persistence
- **Responsive Design** - Mobile-friendly layout

---

## 🤝 Contributing

Contributions are welcome! Here's how you can help:

1. **Fork the repository**
2. **Create a feature branch**
   ```bash
   git checkout -b feature/AmazingFeature
   ```
3. **Commit your changes**
   ```bash
   git commit -m 'Add some AmazingFeature'
   ```
4. **Push to the branch**
   ```bash
   git push origin feature/AmazingFeature
   ```
5. **Open a Pull Request**

### Ideas for Contribution

- [ ] Add export to CSV/PDF functionality
- [ ] Implement recurring expenses
- [ ] Add income tracking
- [ ] Create expense reports
- [ ] Add multi-currency support
- [ ] Implement data backup/restore
- [ ] Add expense reminders

---

---

## 📧 Contact

**Himanshu Sangwan**

- GitHub: [@himanshusangwan2108-netizen](https://github.com/himanshusangwan2108-netizen)
- Project Link: [https://github.com/himanshusangwan2108-netizen/Spend_Tracker](https://github.com/himanshusangwan2108-netizen/Spend_Tracker)

---

## 🌟 Show Your Support

If you find this project helpful, please give it a ⭐️!

---

## 🔮 Future Enhancements

- Cloud sync functionality
- Mobile app version
- Advanced analytics and insights
- Multiple user accounts
- Category budgets
- Receipt scanning (OCR)
- Financial goal setting

---

<p align="center">Made with ❤️ by Himanshu Sangwan</p>
