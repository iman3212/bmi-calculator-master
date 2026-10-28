# ⚖️ BMI Calculator

<div align="center">

  <img src="https://capsule-render.vercel.app/api?type=rounded&color=0:141E30,100:243B55&height=180&section=header&text=BMI%20Calculator&fontSize=42&fontColor=ffffff&animation=fadeIn" width="100%" alt="BMI Calculator Header" />

  <h3>A Simple and User-Friendly Body Mass Index Calculator</h3>

  <p>
    Calculate your Body Mass Index, understand your BMI category, and track your progress over time.
  </p>

  <img src="https://img.shields.io/badge/React-Hooks-61DAFB?style=for-the-badge&logo=react&logoColor=black" alt="React" />
  <img src="https://img.shields.io/badge/JavaScript-ES6+-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black" alt="JavaScript" />
  <img src="https://img.shields.io/badge/LocalStorage-Data%20Persistence-2C5364?style=for-the-badge" alt="LocalStorage" />
  <img src="https://img.shields.io/badge/Responsive-Design-38B2AC?style=for-the-badge" alt="Responsive Design" />

<br /><br />

**Developed by [Iman](https://github.com/iman3212)**

</div>

---

## 📌 About The Project

BMI Calculator is a web application designed to calculate Body Mass Index (BMI)
using a person's height and weight.

The application provides a simple way to calculate BMI, view the corresponding
BMI category, and keep track of previous measurements.

This project demonstrates practical frontend development concepts, including
React Hooks, user input handling, calculation logic, browser storage, and
responsive user interfaces.

## ✨ Features

- ⚖️ **BMI Calculation:** Calculate Body Mass Index using height and weight.
- 📊 **BMI Categories:** Display the category associated with the calculated
  BMI.
- 💾 **Local Data Storage:** Keep measurement records in the browser.
- 📅 **Measurement History:** Store and review recent BMI measurements for up to
  seven days.
- ⚛️ **React Hooks:** Manage component state and application behavior using
  React Hooks.
- 📱 **Responsive Interface:** Support a user-friendly experience across
  different screen sizes.
- 🎨 **Clean UI:** Provide a straightforward interface for entering measurements
  and viewing results.
- ⚡ **Instant Results:** Calculate BMI from the provided measurements.

## 🛠️ Built With

| Technology        | Purpose                                   |
| ----------------- | ----------------------------------------- |
| React             | Building the user interface               |
| JavaScript (ES6+) | BMI calculation and application logic     |
| React Hooks       | Managing component state and behavior     |
| HTML5             | Structuring application content           |
| CSS3              | Styling and responsive layouts            |
| LocalStorage      | Saving measurement history in the browser |
| Create React App  | Project setup and development workflow    |

## 🧮 BMI Formula

BMI is calculated by dividing body weight by the square of height.

\[ BMI = \frac{\text{Weight (kg)}}{\text{Height (m)}^2} \]

### Example

Suppose a person has the following measurements:

- Height: 170 cm (1.70 m)
- Weight: 65 kg

Calculation:

\[ BMI = \frac{65}{1.70 \times 1.70} \]

**Result: BMI ≈ 22.49**

## 📊 BMI Categories

The following categories are commonly used for adults:

| BMI Range      | Category      |
| -------------- | ------------- |
| Below 18.5     | Underweight   |
| 18.5 – 24.9    | Normal weight |
| 25.0 – 29.9    | Overweight    |
| 30.0 and above | Obesity       |

> **Disclaimer:** BMI is a general screening measure, not a diagnosis. It does
> not independently determine a person's overall health.

## 🚀 Getting Started

Follow these instructions to run the project on your local machine.

### Prerequisites

Make sure you have the following installed:

- [Node.js](https://nodejs.org/)
- npm (included with Node.js)
- [Git](https://git-scm.com/)

### Installation

**1. Clone the repository**

```bash
git clone https://github.com/iman3212/bmi-calculator.git
```

**2. Navigate to the project directory**

```bash
cd bmi-calculator
```

**3. Install dependencies**

```bash
npm install
```

**4. Start the development server**

```bash
npm start
```

**5. Open the application**

Visit the following URL in your browser:

http://localhost:3000

> These commands assume your repository uses the original Create React App
> setup. If your version uses a different build tool, follow the scripts defined
> in `package.json`.

## 📖 How To Use

1. Open the BMI Calculator application.
2. Enter your height.
3. Enter your weight.
4. Calculate your BMI.
5. Review the calculated result and BMI category.
6. Review previous measurements if history tracking is available.
7. Return later to check your progress while the stored records remain
   available.

## 💾 Data Storage

The application uses browser LocalStorage to retain measurement data between
visits.

LocalStorage allows data to remain available in the same browser without
requiring a separate database or user account.

Depending on the implementation, saved records may be removed when they expire,
are cleared manually, or the browser's stored site data is deleted.

## 📁 Project Structure

The exact file structure may vary depending on the repository version. A typical
React application structure looks like this:

```text
bmi-calculator/
├── public/
├── src/
│   ├── components/
│   ├── App.js
│   ├── App.css
│   ├── index.js
│   └── index.css
├── package.json
├── package-lock.json
└── README.md
```

## 🎯 Learning Objectives

This project provides practical experience with:

- Building user interfaces with React.
- Using React Hooks to manage state.
- Handling form inputs and user interactions.
- Implementing mathematical calculations in JavaScript.
- Persisting data with LocalStorage.
- Organizing frontend application code.
- Creating responsive web interfaces.
- Displaying calculated results in a clear and understandable way.

## 🔮 Future Improvements

Potential improvements for future versions include:

- Add support for metric and imperial units.
- Improve measurement history visualization.
- Add charts to display BMI trends.
- Provide data export functionality.
- Improve keyboard navigation and accessibility.
- Add additional interface customization options.
- Expand automated testing.

## 🤝 Contributing

Contributions, suggestions, and bug reports are welcome.

1. Fork the repository.
2. Create a feature branch:

    ```bash
    git checkout -b feature/your-feature
    ```

3. Commit your changes:

    ```bash
    git commit -m "feat: describe your changes"
    ```

4. Push your branch:

    ```bash
    git push origin feature/your-feature
    ```

5. Open a Pull Request.

## 👨‍💻 Author

**Iman**

- GitHub: [@iman3212](https://github.com/iman3212)
- Projects: [GitHub Repositories](https://github.com/iman3212?tab=repositories)

## 📄 License

Check the repository's `LICENSE` file for the applicable license terms. If no
license file exists, contact the original copyright holder before redistributing
the project.

---

<div align="center">

**Built with ❤️ by [Iman](https://github.com/iman3212)**

⭐ If you find this project useful, consider giving the repository a star!

</div>
