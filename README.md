# Scientific Calculator

A feature-rich scientific calculator built with Java Swing, featuring a modern GUI and comprehensive mathematical operations.

![Java](https://img.shields.io/badge/Java-ED8B00?style=flat&logo=openjdk&logoColor=white)
![Swing](https://img.shields.io/badge/Swing-GUI-blue)

## 🚀 Features

### Basic Operations
- Addition, Subtraction, Multiplication, Division
- Power operations (x^y)
- Percentage calculations
- Sign change (+/-)

### Advanced Functions
- **Trigonometric**: sin, cos, tan (and their inverses)
- **Logarithmic**: log (base 10), ln (natural log)
- **Exponential**: e^x, 10^x
- **Special**: Square root (√), Factorial (n!)

### Additional Features
- **Memory Functions**: Store (MS), Recall (MR), Add (M+), Subtract (M-)
- **Calculation History**: View all previous calculations
- **Keyboard Shortcuts**: Full keyboard support for faster input
- **Error Handling**: Comprehensive validation and error messages

## 🏗️ Architecture

The project follows **Object-Oriented Programming** principles with a clean architecture:

- **Abstract Base Class** (`Operation`): Template for all operations
- **Inheritance Hierarchy**: Specialized operation classes
  - `ArithmeticOperation`
  - `TrigonometricOperation`
  - `LogarithmicOperation`
  - `ExponentialOperation`
  - `SpecialOperation`
- **Engine Pattern** (`CalculatorEngine`): Business logic and state management
- **MVC-inspired GUI** (`CalculatorGUI`): Separation of UI and logic

## 📋 Prerequisites

- Java Development Kit (JDK) 11 or higher
- Any Java IDE (IntelliJ IDEA, Eclipse, NetBeans) or terminal

## 🔧 Installation & Usage

### Option 1: Using an IDE

1. Clone the repository:
```bash
git clone https://github.com/YOUR_USERNAME/scientific-calculator.git
cd scientific-calculator
```

2. Open the project in your IDE

3. Run `Main.java`

### Option 2: Command Line

1. Clone and navigate to the project:
```bash
git clone https://github.com/YOUR_USERNAME/scientific-calculator.git
cd scientific-calculator
```

2. Compile the project:
```bash
javac calculator/*.java
```

3. Run the calculator:
```bash
java calculator.Main
```

## ⌨️ Keyboard Shortcuts

| Key | Action |
|-----|--------|
| `0-9` | Number input |
| `+` `-` `*` `/` | Basic operations |
| `.` | Decimal point |
| `=` or `Enter` | Calculate result |
| `c` | Clear display |
| `Backspace` | Delete last character |

## 🎯 Usage Examples

### Basic Arithmetic
```
5 + 3 = 8
10 * 2 = 20
15 / 3 = 5
```

### Power Operations
```
2 x^y 3 = 8
5 x^y 2 = 25
```

### Trigonometric Functions
```
sin(30°) = 0.5
cos(60°) = 0.5
tan(45°) = 1
```

### Memory Operations
1. Calculate a value: `5 + 3 = 8`
2. Store in memory: Click `MS`
3. Perform other calculations
4. Recall from memory: Click `MR` → displays `8`

## 📁 Project Structure

```
scientific-calculator/
├── calculator/
│   ├── Main.java                      # Entry point
│   ├── CalculatorGUI.java             # User interface
│   ├── CalculatorEngine.java          # Core logic
│   ├── Operation.java                 # Abstract base class
│   ├── ArithmeticOperation.java       # +, -, *, /, ^
│   ├── TrigonometricOperation.java    # sin, cos, tan
│   ├── LogarithmicOperation.java      # log, ln
│   ├── ExponentialOperation.java      # e^x, 10^x
│   └── SpecialOperation.java          # √, !, %, +/-
└── README.md
```

## 🎓 Learning Highlights

This project demonstrates:
- **OOP Principles**: Inheritance, Polymorphism, Encapsulation, Abstraction
- **Design Patterns**: Factory Method, Template Method
- **Java Swing**: GUI development, Event handling, Layouts
- **Exception Handling**: Custom exceptions and error management
- **Data Structures**: StringBuilder for efficient string operations
- **Input Validation**: Comprehensive number and operation validation

## 🐛 Error Handling

The calculator handles various edge cases:
- Division by zero
- Square root of negative numbers
- Logarithm of non-positive numbers
- Factorial overflow (max n=20)
- Invalid trigonometric inputs
- Exponential overflow

## 🔮 Future Enhancements

- [ ] Scientific notation support
- [ ] Graphing capabilities
- [ ] Custom function definitions
- [ ] Unit conversions
- [ ] Expression parsing for complex equations
- [ ] Theme customization

## 👨‍💻 Author

**Frenkli Zeqollari**
- Email: frenklif50@gmail.com

## 📄 License

This project is open source and available under the [MIT License](LICENSE).

## 🙏 Acknowledgments

- Built as part of Software Engineering studies at University of Europe for Applied Sciences
- Java Swing documentation and community resources
