# Lovely_loveseats_codecademy
codecademy training =D 
(edited w/ VSCode THANK YOU!!!!)
# Item descriptions and prices
lovely_loveseat_description = 'Lovely Loveseat. Tufted polyester blend on wood. 32 inches high x 40 inches wide x 30 inches deep. Red or white.'
lovely_loveseat_price = 254.00
stylish_settee_description = 'Stylish Settee. Faux leather on birch. 29.50 inches high x 54.75 inches wide x 28 inches deep. Black.'
stylish_settee_price = 180.50
luxurious_lamp_description = 'Stylish Settee. Faux leather on birch. 29.50 inches high x 54.75 inches wide x 28 inches deep. Black.'
luxurious_lamp_price = 52.15

# Sales tax rate
sales_tax = 0.088

# Customer one
customer_one_itemization = [lovely_loveseat_description, luxurious_lamp_description]
customer_one_total = lovely_loveseat_price + luxurious_lamp_price
customer_one_tax = round(customer_one_total * sales_tax)
customer_one_total += customer_one_tax

# Print the itemization and total cost for customer one
print('Customer one items:')
for item in customer_one_itemization:
    print('- ' + item)
print('Total cost: ${:.2f}'.format(customer_one_total))

