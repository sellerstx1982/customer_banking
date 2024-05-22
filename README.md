# Customer Banking
My coding project uses Python to create a customer banking system with options for a savings account and certified deposit account. I wanted a task where I could create and use functions to determine someone's ending balance by using a beginning balance, interest rate, and months to maturity.

## Throughout this experience I learned how to:
1) Import and define functions.
2) Instantiating objects.
3) Pass in arguments.
4) Type conversions.
5) Call main functions.

To begin the process, press the run button on the customer_banking.py file using any source code editor compatible with Python. The code starts by prompting the user to enter their current savings balance first. Please remember to leave out commas for numbers over a thousand, but a decimal place for cents is acceptable. Once the balance is entered the user is prompted to enter the interest rate for the savings account. The entry is the monthly percentage rate for the savings account. A modulus is not needed upon entering the interest rate. If a modulus is entered with the interest rate, then the user is required to rerun the program and start again. After a valid response is made for the interest rate the user is asked how many months until the savings account matures. Only integers are acceptable for the amount of months and if a float is entered, the user is required to restart the process again from the start. When prompt for entering the amount of months until maturity is correctly followed, the future savings balance is provided, along with the amount of interest earned during the time until the savings account matures. Along with the future savings balance and savings interest earned, the user is prompted to proved their current CD balance and the same process is repeated, only using the CD account instead of the savings. The program concludes by providing the user with their future CD balance and the interest earned on the CD during the months until maturity.
