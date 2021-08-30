# Codecademy -- Sal's-Shipping

# This program is to ask user for the weight of package and tells which method of shipping is cheapest, and how much will it cost to ship package using Sal's Shippers.

# create a weight variable
weight = 41.5

# Ground Shipping
if weight <= 2:
  cost_ground = weight * 1.5 + 20
elif weight > 2 and weight <= 6:
  cost_ground = weight * 3 + 20
elif weight > 6 and weight <= 10:
  cost_ground = weight * 4 + 20
else:
  cost_ground = weight * 14.25 + 20

# Test cost_ground shipping function
print("Ground Shipping: $" + str(round(cost_ground, 2)))

# create a variable for the cost of premium ground shipping
premium_ground = 125.00

# print out premium_ground
print("Ground Shipping Premium: $" + str(round(premium_ground, 2)))

# Drone Shipping
if weight <= 2:
  cost_ground = weight * 4.5 + 0
elif weight > 2 and weight <= 6:
  cost_ground = weight * 9 + 0
elif weight > 6 and weight <= 10:
  cost_ground = weight * 12 + 0
else:
  cost_ground = weight * 14.25 + 0

# Test the Drone Shipping condition
print("Drone Shipping: $" + str(round(cost_ground, 2)))

# Test all codes one last time

# What is the cheapest method of shipping a 4.8 lb package and how much?
   # Ground Shipping is $34.4
   # Ground Shipping Premium is $125.0
   # Drone Shipping is $43.2

# What is the cheapest method of shipping a 41.5 lb package and how much would it cost?
   # Ground Shipping is $611.38
   # Ground Shipping Premium is $125.0
   # Drone Shipping is $591.38
