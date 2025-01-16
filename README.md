# sus_sirene

20221 pavi mazni banici sus sirene


# Build Documentation for Simple Calculator

## Prerequisites

Before you can build and run the Simple Calculator, make sure you have the following software installed:

- **Java Development Kit (JDK)**: Version 8 or later.
- **IDE (Optional)**: Any Java IDE (e.g., IntelliJ IDEA, Eclipse, or NetBeans) or a text editor like VS Code to write and edit the Java code.
- **Command Line Tools (Optional)**: If you prefer to build from the command line, ensure you have access to `javac` (Java compiler) and `java` (Java runtime).

### Steps to Build and Run the Application

#### 1. Clone the Repository

To get started, clone the repository to your local machine using Git:

```bash
git clone https://github.com/your-username/Mazni-banici


# Use Cases for Simple Calculator

## Use Case 1: Perform Addition

**Description**:  
The user wants to add two numbers together.

**Preconditions**:  
- The user has opened the calculator.

**Basic Flow**:  
1. The user selects the **Addition** operation from the menu.
2. The user inputs two numbers.
3. The calculator adds the two numbers and displays the result.

**Example**:  
- User inputs `5` and `3`.
- The result will be `8`.

**Postconditions**:  
- The result of the addition is displayed to the user.

---

## Use Case 2: Perform Subtraction

**Description**:  
The user wants to subtract one number from another.

**Preconditions**:  
- The user has opened the calculator.

**Basic Flow**:  
1. The user selects the **Subtraction** operation from the menu.
2. The user inputs two numbers.
3. The calculator subtracts the second number from the first and displays the result.

**Example**:  
- User inputs `10` and `4`.
- The result will be `6`.

**Postconditions**:  
- The result of the subtraction is displayed to the user.

---

## Use Case 3: Perform Multiplication

**Description**:  
The user wants to multiply two numbers.

**Preconditions**:  
- The user has opened the calculator.

**Basic Flow**:  
1. The user selects the **Multiplication** operation from the menu.
2. The user inputs two numbers.
3. The calculator multiplies the two numbers and displays the result.

**Example**:  
- User inputs `4` and `5`.
- The result will be `20`.

**Postconditions**:  
- The result of the multiplication is displayed to the user.

---

## Use Case 4: Perform Division

**Description**:  
The user wants to divide one number by another.

**Preconditions**:  
- The user has opened the calculator.
- The user has entered valid input.

**Basic Flow**:  
1. The user selects the **Division** operation from the menu.
2. The user inputs two numbers.
3. The calculator divides the first number by the second and displays the result.

**Example**:  
- User inputs `10` and `2`.
- The result will be `5`.

**Postconditions**:  
- The result of the division is displayed to the user.

**Exception Flow**:  
- If the second number is `0`, the calculator will display an error message, "Error: Division by zero is not allowed."

---

## Use Case 5: Invalid Operation

**Description**:  
The user selects an invalid operation.

**Preconditions**:  
- The user has opened the calculator.

**Basic Flow**:  
1. The user selects an invalid option (an option outside of the available operations).
2. The calculator displays an error message, "Invalid operation choice."

**Postconditions**:  
- The calculator returns to the main menu.

# User Stories for Simple Calculator

## User Story 1: As a User, I want to perform an addition so that I can add two numbers together.

**Acceptance Criteria**:
- The user can select the addition operation.
- The user can input two numbers.
- The calculator displays the correct result of adding the two numbers.

**Example**:
- User inputs `4` and `6`.
- The calculator displays `10`.

---

## User Story 2: As a User, I want to perform a subtraction so that I can subtract one number from another.

**Acceptance Criteria**:
- The user can select the subtraction operation.
- The user can input two numbers.
- The calculator displays the correct result of subtracting the second number from the first.

**Example**:
- User inputs `9` and `3`.
- The calculator displays `6`.

---

## User Story 3: As a User, I want to perform a multiplication so that I can multiply two numbers.

**Acceptance Criteria**:
- The user can select the multiplication operation.
- The user can input two numbers.
- The calculator displays the correct result of multiplying the two numbers.

**Example**:
- User inputs `5` and `7`.
- The calculator displays `35`.

---

## User Story 4: As a User, I want to perform a division so that I can divide one number by another.

**Acceptance Criteria**:
- The user can select the division operation.
- The user can input two numbers.
- The calculator displays the correct result of dividing the first number by the second.
- If the second number is `0`, the calculator displays an error message "Error: Division by zero is not allowed."

**Example**:
- User inputs `10` and `2`.
- The calculator displays `5`.

**Edge Case**:
- User inputs `10` and `0`.
- The calculator displays "Error: Division by zero is not allowed."

---

## User Story 5: As a User, I want to select a valid operation so that I can ensure the calculator works as expected.

**Acceptance Criteria**:
- The user can only select from the four available operations: addition, subtraction, multiplication, and division.
- If the user selects an invalid operation, the calculator displays "Invalid operation choice."

**Example**:
- User selects an option not listed (e.g., `5`).
- The calculator displays "Invalid operation choice."
