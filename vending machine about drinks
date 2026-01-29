                                                                                                    #Vending Machine

items = {
    "A1": ("Coffee", 25),
    "A2": ("Tea", 30),                                          #here the codes that i will run it for machine
    "A3": ("Juice", 20),
    "A4": ("Water", 10)
}

print("Welcome to the Vending Machine!")
print("Items available:")                                 #that the machine print when running the code

for key in items:
    name, price = items[key]
    print(key, "-", name, "($", price, ")", sep="")                                     #that is the key for code that i will do it
 
choice = input("Choose an item (A1/A2/A3/A4): ")                                         #chosing the code in the input way

if choice in items:
    item_name, item_price = items[choice]
    money = int(input("Insert money: "))

    if money >= item_price:
        change = money - item_price
        print("You got:", item_name)
        print("Your change is:", change)
    else:
        print("Not enough money. Money returned.")                               #here the money if it is not enough the code will get that
else:
    print("Invalid choice.")                                              # if i will enter the code in wrong way
