 Week_Three_Assignment.
 Define the function
1-def calculate_discount(price, discount_percent):
    if discount_percent >= 20:
        discount = price * (discount_percent / 100)
        final_price = price - discount
        return final_price
    else:
        return price
2-
original_price = float(input("Enter the original price of the item: "))
discount_percent = float(input("Enter the discount percentage: "))

3- Call the function and get the final price
final_price = calculate_discount(original_price, discount_percent)

4- Print the result
if final_price < original_price:
    print(f"Discount applied! Final price is: ${final_price:.2f}")
else:
    print(f"No discount applied. Final price is: ${final_price:.2f}")
