print("Area Calculator Program")

print("1. Rectangle")
print("2. Triangle")
print("3. Circle")

choice = int(input("Choose a shape number: "))

if choice == 1:
    width = float(input("Enter width: "))
    length = float(input("Enter length: "))
    area = width * length
    print("Rectangle area =", area)

elif choice == 2:
    base = float(input("Enter base: "))
    height = float(input("Enter height: "))
    area = 0.5 * base * height
    print("Triangle area =", area)

elif choice == 3:
    radius = float(input("Enter radius: "))
    area = 3.14 * radius * radius
    print("Circle area =", area)

else:
    print("Invalid choice")
