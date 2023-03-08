# Sal's Shipping
# MG

weight = 41.5
"Ground Shipping"
if weight <= 2:
  cost_ground = weight * 1.5 + 20
elif weight <= 6:
  cost_ground = weight * 3 + 20
elif weight <= 10:
  cost_ground = weight * 4 + 20
else:
  cost_ground = weight * 4.75 + 20
print("Ground Shipping", cost_ground)

cost_ground_premium = 125
print("Cost of Premium Ground $", cost_ground_premium)

"Drone Shipping"
if weight <= 2:
    drone_shipping = weight * 4.5
elif weight <= 6:
    drone_shipping = weight * 9
elif weight <=10:
  drone_shipping = weight * 12
else:
  drone_shipping = weight * 14.25

print("Drone Shipping", drone_shipping)
