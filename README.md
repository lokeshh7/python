# python

#.A shop will give discount of 10% if the product_id and product_cost which is accepted from the user,(of purchased quantity) is more than 1000.


product_id=int(input("Enter the product id = "))
product_cost=float(input("Enter the cost of product = "))

if product_cost > 1000:
    total_cost=(product_cost/100)*10
    print("You got a 10% discount since you spen more than 1000,your total bill is = ",total_cost)
else:
    print("Your Total bill is ",product_cost)
