# finance_calculator
This Python code is a financial calculator that allows users to calculate either simple or compound interest for investments, or monthly repayments for a bond (home loan). Here's an explanation of how the code works:


# Features
Simple Interest Calculation: Calculate the total amount after a specified number of years with a fixed interest rate.
Compound Interest Calculation: Calculate the total amount after a specified number of years with interest compounded annually.
Bond Repayment Calculation: Calculate the monthly repayment amount for a home loan based on the loan amount, interest rate, and repayment period.

# Usage
Clone the repository: git clone https://github.com/phomolopp/financial_calculator.git cd finance_calculator

# Run the program
python finance_calculator

# Calculator preview 
Choose either 'ínvestment' or 'bond' from the menu below to proceed:

    Investment    -to calculate the amount of interest you'll earn on interst
    Bond          -to calculate the amount you'll have to pay on a home loan
    Enter: bond
    Enter the present value of the house: 200000
    Enter interest rate: 8
    Enter number of months to repay the bond: 12                                                                                                                                                                     =====================================================
    Estimated Montly payment :R26539.0033848939
    House Value :R200000.0
    Number of months :R12
    Interest Rate :8.0%
=====================================================
Do you want to continue? yes/no :yes

Choose either 'ínvestment' or 'bond' from the menu below to proceed:     

Investment    -to calculate the amount of interest you'll earn on interst
Bond          -to calculate the amount you'll have to pay on a home loan 
Enter: &
Please select only Investment or Bond
Do you want to continue? yes/no :

# License
This project is licensed under the MIT License. See the LICENSE file for details.

# Contributions
Please open an issue or submit a pull request.
=======
## Functions Defined:

     simple_interest(amount, interest, numYears): Calculates the total amount for simple interest based on the formula 
     Total Amount = Principal×(1+Interest Rate100×Number of Years)Total Amount=Principal×(1+ 100Interest Rate× Number of Years).
     
     compound_interest(amount, interest, numYears): Calculates the total amount for compound interest using the formula 
     Total Amount =Principal×(1+Interest Rate100)Number of YearsTotal Amount=Principal×(1+ 100Interest Rate)  Number of Years.
     
     Investment(): 
     -Handles the input and calculation process for investment scenarios, where the user inputs the initial amount, interest rate, number of years, and chooses between simple or compound interest.
     
     Bond():
     -Handles the input and calculation process for bond scenarios, where the user inputs the present value of the house (amount), interest rate, and number of months to repay.

## Main Program Flow:

The program starts with an infinite loop (while True) where it presents a menu to the user to choose between calculating an investment or a bond.
Depending on the user's choice (Investment or Bond), the corresponding function is called to gather input and perform calculations.
After completing a calculation, the program asks the user if they want to continue (myInput = input("Do you want to continue? yes/no :").lower()). If the user enters "no", the loop breaks, and the program ends.
If any exception occurs during the execution of the program, it catches the exception and displays an error message.

## Error Handling:

The try-except block ensures that if any errors occur during the execution of the program (such as invalid input or mathematical errors), it displays a generic error message and terminates gracefully.

## Output:

The program outputs the calculated amounts or monthly payments formatted in a clear manner, ensuring the user understands the results.

#Overall, this code provides a simple and interactive way for users to calculate financial scenarios related to investments (simple or compound interest) and bond repayments. It's structured to handle typical user inputs and potential errors, making it user-friendly for financial calculations.

