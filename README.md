# Coffee Machine Project


# 1. Prompt user by asking “What would you like? (espresso/latte/cappuccino):”
 a. I check the user’s input to decide what to do next.
 b. The prompt shows every time action has completed, e.g. once the drink is
dispensed. The prompt shows again to serve the next customer.

![1](https://github.com/FeyzaKaraoglu/CoffeeMachine/assets/158828423/dc64aea6-4bae-49a8-ae92-318bbe5490a1)

# 2. Turn off the Coffee Machine by entering “off” to the prompt
 a. For maintainers of the coffee machine, they can use “off” as the secret word to turn off
the machine. My code end execution when this happens.

![2](https://github.com/FeyzaKaraoglu/CoffeeMachine/assets/158828423/c45cdb9a-876b-46c7-bb33-80a5528bced5)

 # 3. Print report
 a. When the user enters “report” to the prompt, a report  generates that shows
the current resource values. e.g.
Water: 100ml
Milk: 50ml
Coffee: 76g
Money: $2.5

![3](https://github.com/FeyzaKaraoglu/CoffeeMachine/assets/158828423/e318dae2-971f-4fa3-a603-7ced4087d610)

# 4.Check resources sufficient?
a. When the user chooses a drink, the program checks if there are enough
resources to make that drink.
b. E.g. if Latte requires 200ml water but there is only 100ml left in the machine. It is
not continue to make the drink but print: “Sorry there is not enough water.”
c. The same happens if another resource is depleted, e.g. milk or coffee.

![image](https://github.com/FeyzaKaraoglu/CoffeeMachine/assets/158828423/75dc115d-7c64-4690-a6a5-d088feeb0be1)



# 5.Process coins.
a. If there are sufficient resources to make the drink selected, then the program 
prompts the user to insert coins.
b. Remember that quarters = $0.25, dimes = $0.10, nickles = $0.05, pennies = $0.01
c. It calculates the monetary value of the coins inserted. E.g. 1 quarter, 2 dimes, 1 nickel, 2
pennies = 0.25 + 0.1 x 2 + 0.05 + 0.01 x 2 = $0.52

# 6. Check transaction successful?
a. It checks that the user has inserted enough money to purchase the drink they selected.
E.g Latte cost $2.50, but they only inserted $0.52 then after counting the coins the
program says “Sorry that's not enough money. Money refunded.”.

![image](https://github.com/FeyzaKaraoglu/CoffeeMachine/assets/158828423/9f16cff2-7bbf-409f-bc46-c9c105ce9941)


b. But if the user has inserted enough money, then the cost of the drink gets added to the
machine as the profit and this will be reflected the next time “report” is triggered. E.g.
Water: 100ml
Milk: 50ml
Coffee: 76g
Money: $2.5
c. If the user has inserted too much money, the machine offers change.
E.g. “Here is $2.45 dollars in change.” The change roundes to 2 decimal
places.



#  7. Make Coffee
a. If the transaction is successful and there are enough resources to make the drink the
user selected, then the ingredients to make the drink should be deducted from the
coffee machine resources.
E.g. report before purchasing latte:
Water: 300ml
Milk: 200ml
Coffee: 100g
Money: $0
Report after purchasing latte:
Water: 100ml
Milk: 50ml
Coffee: 76g
Money: $2.5
b. Once all resources have been deducted, tell the user “Here is your latte. Enjoy!”. If
latte was their choice of drink.

![5](https://github.com/FeyzaKaraoglu/CoffeeMachine/assets/158828423/76d18773-a5b6-471f-a4be-43c222a11973)


# Contributions: 
I am waiting for the feedback of my project, I hope it worked for you.
Enjoy your coffee :)

# Author:  
:octocat: Feyza Karaoğlu
