BMI Calculator
This is a simple Java console application that calculates a user's Body Mass Index (BMI) based on their weight in pounds and height in meters. The program then classifies the BMI into standard health categories.

Features
Converts weight from pounds to kilograms.

Computes BMI using the formula:
BMI = weight (kg) / (height (m) × height (m))

Categorizes BMI as:

Underweight

Healthy weight

Overweight

Obese

Requirements
Java JDK 8 or higher

How to Run
Clone or download the repository.

Compile the Java file:

bash
Copy
Edit
javac BMIcalculator.java
Run the compiled program:

bash
Copy
Edit
java BMIcalculator
Enter your weight in pounds and height in meters when prompted.

Example
yaml
Copy
Edit
Enter your weight in Pounds: 
150
Enter your height in meters: 
1.75
Your BMI is: 24.49
You are Healthy weight
Notes
1 pound is converted to kilograms using the factor 0.453592.

BMI ranges are based on commonly accepted health standards.

