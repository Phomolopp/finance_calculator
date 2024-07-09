# finance_calculator
This Python code is a financial calculator that allows users to calculate either simple or compound interest for investments, or monthly repayments for a bond (home loan). Here's an explanation of how the code works:

## Functions Defined:

     simple_interest(amount, interest, numYears): Calculates the total amount for simple interest based on the formula 
     Total Amount = Principal×(1+Interest Rate100×Number of Years)Total Amount=Principal×(1+ 100Interest Rate× Number of Years).
     
     compound_interest(amount, interest, numYears): Calculates the total amount for compound interest using the formula 
     Total Amount =Principal×(1+Interest Rate100)Number of YearsTotal Amount=Principal×(1+ 100Interest Rate)  Number of Years.
     
     Investment(): 
     Handles the input and calculation process for investment scenarios, where the user inputs the initial amount, interest rate, number of years, and chooses between simple or compound interest.
     
     Bond():
     Handles the input and calculation process for bond scenarios, where the user inputs the present value of the house (amount), interest rate, and number of months to repay.

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
