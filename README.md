# JavaScript Calculator

A fully functional, responsive calculator web application built with vanilla JavaScript, HTML5, and CSS3, featuring a clean modern UI and comprehensive error handling.

![Calculator Screenshot]<img width="1918" height="918" alt="image" src="https://github.com/user-attachments/assets/dc7345b4-2617-4d23-bc13-7ec78d9141f2" />


## 📋 About The Project

This calculator application was built to demonstrate frontend development fundamentals and clean UI/UX design principles. It solves the need for a simple, accessible calculation tool while showcasing modern web development best practices including responsive design, keyboard accessibility, and robust error handling.

The project emphasizes:
- Clean, maintainable JavaScript code
- Mobile-first responsive design approach
- User experience and accessibility considerations

### Key Features

- ✅ **Core Mathematical Operations** - Addition, subtraction, multiplication, and division 
- ✅ **Error Handling** - Graceful handling of edge cases like division by zero and invalid inputs
- ✅ **Responsive Design** - Mobile-first interface using CSS Grid and Flexbox, works seamlessly on all devices
- ✅ **Keyboard Support** - Full keyboard navigation and input for enhanced accessibility
- ✅ **Clean UI/UX** - Modern, intuitive interface with smooth visual feedback and clear display
- ✅ **Accessibility** - ARIA labels and semantic HTML for screen reader compatibility

### Built With

- **HTML5** - Semantic markup structure
- **CSS3** - Modern styling with Grid and Flexbox
- **JavaScript (ES6+)** - Vanilla JavaScript for core functionality
- **No frameworks or libraries** - Pure frontend fundamentals

## 🚀 Getting Started

### Prerequisites

All you need is a modern web browser:
- Chrome, Firefox, Safari, or Edge (latest versions)
- No server or build tools required

### Installation

1. Clone the repository
   ```bash
   git clone https://github.com/your-username/javascript-calculator.git
   ```

2. Navigate to project directory
   ```bash
   cd javascript-calculator
   ```

3. Open in browser
   ```bash
   # Simply open index.html in your browser
   # Or use a local server:
   python -m http.server 8000
   # OR
   npx serve
   ```

4. Visit `http://localhost:8000` (if using local server) or just open `index.html` directly

### Quick Deploy to GitHub Pages

1. Push your code to GitHub
2. Go to repository Settings → Pages
3. Select `main` branch → Save
4. Your calculator will be live at `https://your-username.github.io/javascript-calculator`

## 💻 Code Highlights

### JavaScript Functionality
```javascript
// Clean operator handling with error prevention
function calculate(num1, operator, num2) {
    switch(operator) {
        case '+': return num1 + num2;
        case '-': return num1 - num2;
        case '*': return num1 * num2;
        case '/': 
            if(num2 === 0) {
                displayError('Cannot divide by zero');
                return null;
            }
            return num1 / num2;
        default: return num2;
    }
}
```

### Responsive CSS Grid Layout
```css
.calculator {
    display: grid;
    grid-template-columns: repeat(4, 1fr);
    gap: 10px;
    max-width: 400px;
    margin: 0 auto;
}
```

## 🎯 What I Learned

- **DOM Manipulation** - Dynamic updates to display and handling user input events
- **Event Handling** - Click events, keyboard events, and event delegation patterns
- **CSS Layout Techniques** - Mastering Grid and Flexbox for responsive component design
- **Error Handling** - Implementing graceful error handling for edge cases and user mistakes
- **Accessibility** - Adding ARIA labels, keyboard navigation, and semantic HTML
- **UX Design Principles** - Creating intuitive interfaces with visual feedback and clear affordances
- **Code Organization** - Structuring vanilla JavaScript for maintainability and readability

## 🔮 Future Improvements

- [ ] Add scientific calculator mode (trigonometric functions, square root, exponents)
- [ ] Implement calculation history with the ability to recall previous operations
- [ ] Add theme toggle (dark mode / light mode)
- [ ] Support for more complex expressions (parentheses, order of operations)
- [ ] Add keyboard shortcut guide/tooltip
- [ ] Implement memory functions (M+, M-, MR, MC)
- [ ] Add percentage calculations
- [ ] Include sound effects for button clicks (with mute option)

## 🧪 Testing

**Tested on:**
- ✅ Chrome 120+ (Desktop & Mobile)
- ✅ Firefox 121+
- ✅ Safari 17+ (iOS & macOS)
- ✅ Edge 120+

**Test Cases Covered:**
- Basic arithmetic operations
- Decimal number handling
- Division by zero error
- Multiple sequential operations
- Keyboard input validation
- Responsive behavior on various screen sizes

## 📱 Responsive Design

The calculator is fully responsive and optimized for:
- 📱 **Mobile** (320px - 480px) - Touch-optimized button sizes
- 📱 **Tablet** (481px - 768px) - Balanced layout
- 💻 **Desktop** (769px+) - Centered with max-width constraint

## 🎨 Design Decisions

**Color Scheme:**
- Primary: Clean, modern neutrals for calculator body
- Accent: Vibrant color for operation buttons to aid visual distinction
- Display: High contrast for readability

**Typography:**
- Monospace font for display to ensure consistent number width
- Sans-serif for buttons ensuring clarity at all sizes

**Layout:**
- 4-column grid matching standard calculator layout
- Equal button sizing for consistent touch targets
- Generous spacing for easy interaction on touch devices

## 📝 License

This project is open source and available.

## 👤 Author

**Nhlonipho Ndadane**
- LinkedIn: [@nhlonipho-ndadane](https://linkedin.com/in/nhlonipho-ndadane)
- GitHub: [@your-username](https://github.com/your-username)
- Email: ndadanenhlonipho@gmail.com

**Portfolio:** [View More Projects](https://github.com/Ndadane)

## 🙏 Acknowledgments

- Inspired by the iOS calculator design for clean, minimalist aesthetics
- MDN Web Docs for JavaScript and CSS reference
- FNB App Academy for foundational full stack development training
- W3C ARIA guidelines for accessibility best practices

## 🌟 Project Context

This calculator was built as part of my journey learning frontend development fundamentals during the FNB App Academy Full Stack Development program (2025). It demonstrates mastery of HTML, CSS, and vanilla JavaScript without relying on frameworks or libraries.

---

**⭐ If you found this project helpful, please consider giving it a star!**

---

## 📊 Project Stats

- **Lines of Code:** ~100 (HTML + CSS + JS combined)
- **Build Time:** 5-10 hours
- **Technologies:** 3 (HTML5, CSS3, JavaScript)
- **Dependencies:** 0 (pure vanilla implementation)
