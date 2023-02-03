# sip-calculator-code-in-html
This is a SIP (Systematic Investment Plan) calculator, which helps to calculate the future value of an investment made through regular investments. The user is prompted to input the following details:

Investment Amount: The amount that the user wants to invest on a regular basis.

Investment Period (in years): The duration in years for which the user wants to invest.

Annual Interest Rate (%): The expected annual rate of return on the investment.

The script then calculates the future value of the investment based on the user inputs. The formula used to calculate the future value is:

futureValue = investmentAmount * (Math.pow((1 + monthlyRate), investmentPeriod * 12) - 1) * (1 + monthlyRate) / monthlyRate

Where,

investmentAmount = The amount invested by the user.

investmentPeriod = The duration of the investment in years.

interestRate = The expected annual rate of return.
