# Problem3
# Problem 3: Order Shipping

# Get user input for number of books and cost per book
num_books = int(input("Enter the number of books to order: "))
cost_per_book = float(input("Enter the cost per book: "))

# Calculate order total
order_total = num_books * cost_per_book

# Determine shipping charge
if order_total > 50.00:
    shipping_charge = 0
else:
    shipping_charge = 25.00

# Display results
print(f"\nOrder Total: ${order_total:.2f}")
print(f"Shipping Charge: ${shipping_charge:.2f}")
