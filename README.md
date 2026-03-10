income = float(input("Enter your income: "))

if income <= 150000:
    print("No need to pay tax")
elif income <= 250000:
    tax = income * 0.10
    print("Your tax amount is", tax)
else:
    tax = income * 0.15
    print("Your tax amount is", tax)
