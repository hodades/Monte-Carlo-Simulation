# Monte-Carlo-Simulation
Monte Carlo simulations are commonly employed to gauge the risk associated with a particular trading strategy, such as options or stocks.

import random

def rollDice():
    roll = random.randint(1,100)
    return roll

# Now, just to test our dice, let's roll the dice 100 times. 

x = 0
while x < 100:
    result = rollDice()
    print(result)
    x+=1
