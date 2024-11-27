x1 = float(input("Enter x1 coordinates:"))
x2 = float(input("Enter x2 coordinates:"))
y1 = float(input("Enter y1 coordinates:"))
y2 = float(input("Enter y2 coordinates:"))

#Calculation below

dx_squared: float = x2 - x1
dy_squared: float = y2 - y1

#Calculate the distance square

Distance_Squared: float = dx_squared + dy_squared

#Calculate the actual distance for the square feet

Distance = Distance_Squared ** 0.5

#Output the results

print(f"distance between the points is {Distance_Squared ** 0.5}")
