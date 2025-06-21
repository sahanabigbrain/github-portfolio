print("Welcome to the ultimate tip calculator!")

bill = float(input("How much was your bill bud? $"))

tip = int(input("How tight are you feeling? How much percent are you willing to tip today?"))

split = int(input("Ensure nobody runs off to the bathroom to avoid paying for the bill. How many people are going to split the bill?"))

cost_per_person = (bill * (1 + tip / 100)) / split

print (f"The cost of the bill is ${cost_per_person:.2f} each.")





























