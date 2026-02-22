# PRODIGY-ST-01
# Task 01 – Test Cases for Simple Calculator

## Aim
The aim of this task is to write test cases for a simple calculator application and check whether it is working properly for different types of inputs. The test cases help to verify that the calculator gives correct results for valid inputs and shows proper error messages for invalid inputs.

## Application Overview

The calculator application is used to perform basic mathematical operations like addition, subtraction, multiplication and division. It accepts positive numbers, negative numbers and decimal values. The calculator should also follow the BODMAS rule while evaluating expressions.

## Test Cases

### Test Case ID: TC_01

**Description:** Check addition of two positive numbers
**Precondition:** Calculator application should be opened
**Test Steps:**

1. Enter number 5
2. Enter number 3
3. Click on add (+)
   **Expected Result:**
   Result should be displayed as 8

---

### Test Case ID: TC_02

**Description:** Check subtraction operation
**Precondition:** Calculator application should be opened
**Test Steps:**

1. Enter number 10
2. Enter number 4
3. Click on subtract (−)
   **Expected Result:**
   Result should be displayed as 6

---

### Test Case ID: TC_03

**Description:** Check multiplication of two numbers
**Precondition:** Calculator application should be opened
**Test Steps:**

1. Enter number 6
2. Enter number 7
3. Click on multiply (×)
   **Expected Result:**
   Result should be displayed as 42

---

### Test Case ID: TC_04

**Description:** Check division operation
**Precondition:** Calculator application should be opened
**Test Steps:**

1. Enter number 20
2. Enter number 5
3. Click on divide (÷)
   **Expected Result:**
   Result should be displayed as 4

---

### Test Case ID: TC_05

**Description:** Check addition of negative numbers
**Precondition:** Calculator application should be opened
**Test Steps:**

1. Enter number -4
2. Enter number -6
3. Click on add (+)
   **Expected Result:**
   Result should be displayed as -10

---

### Test Case ID: TC_06

**Description:** Check multiplication with decimal values
**Precondition:** Calculator application should be opened
**Test Steps:**

1. Enter number 2.5
2. Enter number 4
3. Click on multiply (×)
   **Expected Result:**
   Result should be displayed as 10

---

### Test Case ID: TC_07

**Description:** Check BODMAS rule
**Precondition:** Calculator application should be opened
**Test Steps:**

1. Enter expression 2 + 3 × 4
2. Click on calculate
   **Expected Result:**
   Calculator should follow BODMAS and display result as 14

---

### Test Case ID: TC_08

**Description:** Check division by zero
**Precondition:** Calculator application should be opened
**Test Steps:**

1. Enter number 10
2. Enter number 0
3. Click on divide (÷)
   **Expected Result:**
   Calculator should show an error message for division by zero

---

### Test Case ID: TC_09

**Description:** Check non-numeric input
**Precondition:** Calculator application should be opened
**Test Steps:**

1. Enter alphabet character (a)
2. Click on any operation
   **Expected Result:**
   Calculator should display invalid input message

---

### Test Case ID: TC_10

**Description:** Check empty input
**Precondition:** Calculator application should be opened
**Test Steps:**

1. Do not enter any value
2. Click on any operation
   **Expected Result:**
   Calculator should ask the user to enter a value

---

## Conclusion

By writing the above test cases, different valid and invalid scenarios of the calculator application are tested. These test cases help in identifying errors and ensure that the calculator works correctly for basic mathematical operations.


