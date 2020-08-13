# Points
Python3
points = 174  # use this input to make your submission

# write your if statement here
if  points >= 1 and points <=50:
    prize_name = wooden rabbit
elif  points >= 51 and points <= 150:
    prize_name = no prize
elif  points >= 151 and points <= 180:
    prize_name = wafer-thin mint
else  points >= 181:
    prize_name = penguin
result="Congratulations! You won a {}.".format(prize_name)

print(result)
