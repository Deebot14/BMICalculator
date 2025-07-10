# BMICalculator
This is a personal project to test form interfaces — an Android app that calculates a user's Body Mass Index (BMI) based on their age, gender, height, and weight. The app provides BMI results with context-sensitive feedback depending on the user's age and selected gender.

## Programming Languages / Technologies
Java, Android SDK, Material Design Components, DecimalFormat, View Binding (findViewById)

## Features
- ### User Input Form
Includes input fields for age, gender (radio buttons), height (feet and inches), and weight (kg).

- ### BMI Calculation
Converts height from feet/inches to meters and computes BMI using the standard formula. Displays the BMI value with two-decimal precision.

- ### Result Feedback

  For users 18 and older: displays whether the user is underweight, healthy, or overweight.

  For users under 18: provides guidance to consult a doctor based on the selected gender.

- ### Interactive UI
Includes a responsive calculate button and real-time form validation feedback through toast messages and result text updates.
