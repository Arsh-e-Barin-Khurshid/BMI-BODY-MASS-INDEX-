
# BMI (Body Mass Index) Calculator using Python




## 1. Project Description

This Python program calculates the Body Mass Index (BMI) based on user input for height (in inches) and weight (in pounds). The BMI is then used to determine the weight category of the user according to standard BMI ranges. The categories include Severely Underweight, Underweight, Normal, Overweight, Moderately Obese, Severely Obese, and Morbidly Obese.
## 2. Features 

>User Input: The program prompts the user to input their height in inches and weight in pounds.

BMI Calculation:
Uses the BMI formula:

BMI = weight in pounds × 703/(height in inches)2

1. Categorization: Classifies the calculated BMI into one of several weight categories.

2. Output: Displays the BMI and the corresponding weight category.
## 3. Installation

To run this program, you need to have Python installed on your computer. You can download Python from the official Python website.
## 4. Usage

1. Clone the repository or download the bmi_calculator.py file.
2. Open a terminal or command prompt and navigate to the directory containing the bmi_calculator.py file.
3. Run the program by executing the following command:
    python bmi_calculator.py
4. Enter your height in inches and weight in pounds when prompted.





## 5. Code Example

Here's a sample of the code used in the program:

BMI Calculator in Python

Taking user input for height and weight

height = float(input("What is your height (in inches): "))
weight = float(input("What is your weight (in lbs): "))

Calculating BMI

bmi = weight * 703 / height ** 2
bmi = round(bmi, 2)

Determining the BMI category

if bmi < 16:

    category = "Severely Underweight"
    
    elif bmi < 18.4:
    category = "Underweight"

elif bmi < 24.9:

    category = "Normal"

elif bmi < 29.9:

    category = "Overweight"

elif bmi < 34.9:

    category = "Moderately Obese"

elif bmi < 39.9:

    category = "Severely Obese"
    
else:

    category = "Morbidly Obese"

Displaying the result

print(f"Your BMI of {bmi} makes you {category}")


## 6. Functionality

1. Height Input: Prompts the user to enter their height in inches.
2. Weight Input: Prompts the user to enter their weight in pounds.
3. BMI Calculation: Computes the BMI using the provided height and weight.
4. Category Determination: Uses if and elif statements to determine the BMI category based on the calculated BMI.
5. Output Display: Prints the BMI and corresponding weight category using an f-string.


## 7. Contribution

Contributions are welcome! If you find any issues or have suggestions for improvements, please create a pull request or submit an issue.

## 8. Creator

This project was created by Arshebarin Khurshid. Feel free to reach out for any questions or suggestions.
## 9. Acknowledgements

1. Inspired by the need for a simple and easy-to-use BMI calculator.

2. Thanks to the Python community for their support and resources


## 10. Contact Information

Email: sultantahira5gmail.com

LinkedIn: Arshebarin Khurshid