# -buying-banana-apples-mango-using-if-ifelse-nested-if-add-fuction
fruits=(input("enter the fruits (apple/mango/banana)?"))

bill=0
if fruits =='apple' or fruits =='apple':
    bill=100
    print("apples price is 100 ")
elif fruits=='mango' or fruits=='mango':
    bill=200
    print("mango price is 200")
else:
    bill=300
    print("banana price is 300")
add_orange=(input("do you have oranges(y/n)?"))
if add_orange=='y' or add_orange=='y':
    bill+=200
    print("price of oranges 200")
add_tomato=(input("do you want tomato(y/n)?"))
if add_tomato=='y' or add_tomato=='y':
    bill+=100
    print("the price of tomato is 100 ")
print(f"total bill is {bill}")
