# 📊 GPA Calculator

A secure, user-friendly web application for calculating GPA (Grade Point Average) and percentage based on subject-wise marks. This tool helps students quickly compute their academic performance metrics.

## 🌟 Features

- **Interactive Input**: Add multiple subjects with obtained and total marks
- **Real-time Calculation**: Calculate GPA, percentage, and grades instantly
- **Subject Management**: Delete subjects individually from the calculation
- **Keyboard Shortcuts**: 
  - Press `SHIFT` to calculate results
  - Press `ENTER` to navigate between input fields
  - Use `Arrow Keys` to move between fields
- **Responsive Design**: Works seamlessly on desktop and mobile devices
- **Secure**: Implements input validation and XSS protection
- **No Dependencies**: Pure HTML, CSS, and JavaScript - no external libraries required

## 🔒 Security Features

- **Content Security Policy (CSP)**: Prevents XSS attacks
- **Input Sanitization**: All user inputs are sanitized to prevent code injection
- **Validation**: 
  - Prevents negative marks
  - Ensures obtained marks don't exceed total marks
  - Validates non-zero total marks
  - Limits subject name length
- **Safe DOM Manipulation**: Uses secure DOM methods instead of innerHTML

## 🚀 Getting Started

### Prerequisites

- A modern web browser (Chrome, Firefox, Safari, Edge)
- No installation required!

### Usage

1. **Open the Application**: 
   - Live: [https://anacondy.github.io/GPA-calculator/](https://anacondy.github.io/GPA-calculator/)
   - Or open `index.html` in your browser

2. **Add Subjects**:
   - Enter subject name
   - Enter obtained marks
   - Enter total marks
   - Click "➕ Add Subject" or press ENTER

3. **Calculate Results**:
   - Click "Calculate" button or press SHIFT key
   - View your percentage, GPA, and grade

4. **Manage Subjects**:
   - Click the ✖ icon next to any subject to remove it

## 📊 Grading System

| Percentage | Grade | GPA Range |
|------------|-------|-----------|
| 80% - 100% | A+    | 8.0 - 10.0 |
| 70% - 79%  | A     | 7.0 - 7.9  |
| 60% - 69%  | B+    | 6.0 - 6.9  |
| 50% - 59%  | B     | 5.0 - 5.9  |
| Below 50%  | P     | Below 5.0  |

## 🛠️ Technical Details

- **Frontend**: HTML5, CSS3, JavaScript (ES6+)
- **Styling**: Custom CSS with modern design patterns
- **Architecture**: Single-page application (SPA)
- **Compatibility**: Works in all modern browsers

## 📁 Project Structure

```
GPA-calculator/
├── index.html          # Main application file
├── README.md          # This file
├── LICENSE            # MIT License
└── .gitignore         # Git ignore rules
```

## 🤝 Contributing

Contributions are welcome! Please feel free to submit a Pull Request.

## 📄 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## 👨‍💻 Author

**Anuj Meena**

## 🌐 Deployment

This application is deployed on GitHub Pages and is accessible at:
[https://anacondy.github.io/GPA-calculator/](https://anacondy.github.io/GPA-calculator/)

## 📝 Changelog

### Version 2.0 (Current)
- ✅ Added security features (CSP, input sanitization)
- ✅ Enhanced input validation
- ✅ Improved error handling with user-friendly alerts
- ✅ Removed duplicate files
- ✅ Updated documentation

### Version 1.0
- Initial release with basic GPA calculation
- Subject management with delete functionality
- Keyboard shortcuts support

