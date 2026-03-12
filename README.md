total = 0

while True:
    product = input("Enter product name (or 'done' to finish): ")

    if product == "done":
        break

    price = float(input("Enter price: "))
    total += price

print("Total price:", total)

paid = float(input("Enter amount paid: "))

change = paid - total

print("Change:", change)
