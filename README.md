# BMI Calculator 🏋️‍♂️📊

Welcome to the **BMI Calculator** project! This is a simple web-based application that allows users to calculate their **Body Mass Index (BMI)** based on their **height**, **weight**, and **age**. The app also classifies the user's BMI into different categories such as **Underweight**, **Healthy**, **Overweight**, **Obese**, and **Extremely Obese**.

---

## 📜 **Table of Contents**

1. [Introduction](#introduction)

2. [Technologies Used](#technologies-used)

3. [Features](#features)

4. [How to Use](#how-to-use)

5. [File Structure](#file-structure)

6. [Contributing](#contributing)

---

## 🚀 **Introduction**

The **BMI Calculator** helps users easily compute their BMI and provides immediate feedback on their body weight classification. The application uses the **Imperial System** to calculate the BMI but is designed to handle both metric and imperial inputs.

### **Key Features:**

- **Age**: User's age (optional) to personalize the calculation.

- **Gender Selection**: Male or Female to allow BMI calculation based on gender.

- **Height and Weight Inputs**: Allows users to input their height (in cm) and weight (in kg).

- **BMI Calculation**: Calculates BMI using the standard formula:  
  
  \[
  \text{BMI} = \frac{\text{weight (kg)}}{(\text{height (m)})^2}
  \]

- **Feedback**: Displays a classification for the BMI value:
  
  - **Underweight**: BMI < 18.5
  
  - **Healthy**: 18.5 ≤ BMI ≤ 24.9
  
  - **Overweight**: 25 ≤ BMI ≤ 29.9
  
  - **Obese**: 30 ≤ BMI ≤ 34.9
  
  - **Extremely Obese**: BMI ≥ 35

---

## 🛠️ **Technologies Used**

This project is built with the following technologies:

- **HTML**: Structure of the webpage.

- **CSS**: Styling to make the app look appealing and user-friendly.

- **JavaScript**: Functionality for BMI calculation, validation, and result display.

- **FontAwesome**: For adding icons (used for the close button in the modal).

- **Google Fonts**: Used for a clean and modern font style (**Montserrat**).

---

## 🧑‍💻 **Features**

- **User Input Fields**: Collects the user’s age, height, weight, and gender.

- **BMI Calculation**: Uses a standard formula to calculate BMI based on height and weight.

- **Error Handling**: If any field is left empty, a modal shows up to prompt the user to fill out all the required fields.

- **BMI Categories**: Classifies the BMI into one of five categories.

- **Responsive Design**: The app is fully responsive, providing a great experience on both mobile and desktop devices.

- **Clear Results**: The results are clearly shown with a BMI value and a category (e.g., "You are Healthy").

- **Interactive Modal**: If the user misses filling out any input, a modal appears displaying a message.

---

## 📦 **How to Use**

1. **Clone the Repository**  
   
   - Start by cloning the repository to your local machine:
   
   ```bash
   git clone https://github.com/sudhanshu-j/bmi-calculator.git
   ```

2. **Open the `index.html` File**

- After cloning, open the `index.html` file in any web browser (Chrome, Firefox, etc.).

3. **Enter Your Details**

- Fill in the required fields:

   - Age: Enter your age (optional).
   
   - Gender: Select either Male or Female.

   - Height: Enter your height in centimeters.
   
   - Weight: Enter your weight in kilograms.

4. **Calculate Your BMI**

- Click the "Calculate BMI" button to get your BMI and the category.

5. **View Your Results**

- Your BMI will be displayed with a category, for example:

   - You are Healthy with BMI: 22.58

6. **Error Handling**

- If any fields are missing or incomplete, a modal will pop up asking you to complete all fields.

---

## 📂 File Structure

The project is structured as follows:

```bash
bmi-calculator/
├── index.html         # Main HTML file with structure
├── style.css          # Styles for the BMI calculator page
├── script.js          # JavaScript code that calculates BMI and handles interactions
└── README.md          # This README file
```

---

## 🤝 Contributing

If you want to contribute to this project, feel free to fork the repository and make improvements! Here's how you can contribute:

1. **Fork the repository**.

2. **Clone the forked repository to your local machine**.

3. **Create a new branch for your feature or fix**: (` git checkout -b feature/your-feature-name `)

4. **Make your changes and commit them**: (` git commit -m "Add new feature or fix" `)

5. **Push the changes to your repository**: (` git push origin feature/your-feature-name `)

6. **Create a Pull Request and describe your changes**.

---

## 💬 Contact

If you have any questions or suggestions, feel free to open an issue or reach out to me.

Thank you for using the BMI Calculator! 🙌
