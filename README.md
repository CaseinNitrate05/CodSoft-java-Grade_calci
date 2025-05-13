## 🎓 **Project Title**:

**Student Grade Calculator with Input Validation in Java**

---

## 📝 **Project Description**:

The **Student Grade Calculator** is a command-line Java application that accepts marks for multiple subjects, validates inputs, computes total marks and percentage, and assigns individual and overall grades based on predefined grading criteria.

This project demonstrates core Java programming concepts such as:

* **Object-Oriented Programming (OOP)**
* **Custom Exception Handling**
* **Input Validation**
* **Looping and Conditional Logic**

---

## 🎯 **Key Features**:

### 1. **Input Validation with Custom Exception**:

* Uses a user-defined exception `InvalidMarksException` to check for invalid marks (i.e., marks not in the range **0 to 100**).
* Prompts the user to re-enter marks if invalid values are entered.

### 2. **Marks Entry**:

* Allows the user to enter marks for a user-specified number of subjects.
* Stores marks in an array for further processing.

### 3. **Total and Average Calculation**:

* Calculates the **total marks** obtained.
* Computes the **average percentage** using the formula:
  `percentage = (total / (subjects * 100)) * 100`

### 4. **Grade Assignment**:

* Assigns **grades per subject** and **overall grade** based on the following criteria:

  ```
  A+ : 90–100
  A  : 80–89
  B  : 70–79
  C  : 60–69
  D  : 50–59
  E  : 40–49
  F  : Below 40
  ```

### 5. **User-Friendly Output**:

* Outputs are well-formatted with separators to distinguish each section (Total, Average, Grades).

---

## 🛠️ **Technologies Used**:

| Component                  | Description                                       |
| -------------------------- | ------------------------------------------------- |
| **Java**                   | Primary programming language                      |
| **Scanner**                | Used for interactive user input                   |
| **Custom Exception Class** | `InvalidMarksException` handles validation errors |

---

## 📌 **Highlights**:

* Emphasizes **input validation** using custom exceptions.
* Clear separation of functionality:

  * `inputMarks()` – input and validation
  * `calculateTotal()` – calculates sum
  * `avg()` and `average()` – computes and displays percentage
  * `gradeSubject()` – individual subject grades
  * `gradeTotal()` – overall grade
* Structured output for better readability.

---

## 💡 **Possible Enhancements**:

* Add **student name and ID** fields.
* Use **arrays or lists of objects** to handle multiple students.
* Export results to a **text file or database**.
* Build a **GUI version** using Swing or JavaFX.
* Handle **non-numeric input** errors gracefully using `try-catch`.

---

## 🎓 **Learning Outcomes**:

* Understanding of **arrays** and data collection in Java.
* Usage of **custom exception handling**.
* Practice with **looping**, **methods**, and **conditionals**.
* Modular code structure for real-world applications.
