# Wk-3-Assignment
def calculate_discount(price, discount_percent):
    if discount_percent >= 20:
        final_price = price - (price * discount_percent/100)
        return final_price
    else:
        return price

original_price = 1000.0
discount_percent = 25.0
final_price = calculate_discount(original_price, discount_percent)
if final_price != original_price:
    print(f"The final price after applying the discount is: {final_price}")
else:
    print(f"No discount applied. The original price is: {original_price}")
