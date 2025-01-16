# sus_sirene

20221 pavi mazni banici sus sirene


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
