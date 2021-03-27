print("Homework") #print table header for homework (Is there a way to center)

print("How many homework items?")
itemNum  = int(input('Item Number: \n'))
print("Item Number" + "\t" + "Points Earned" "\t" + "Possible Points") #Print sub header

for i in range(1,itemNum+1):
    print(i, "\t")
    pointsEarned = int(input())
   #for j in range(i): Trying to print an inner loop to add user input for points earned and possible points
       # print(pointsEarned, "\t")

# RowdyHacksGC
