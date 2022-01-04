#stone paper seasor 
import random
x=input("pleae enter y to start or e to exit the game:")

while x=="y" or x!="e":
    if x== "y" :
        player=input("please enter one thing from stone peper seasor:")
        list=["stone","paper","seasor"]
        comp=random.choice(list)
        print("comp:",comp)
        if player=="stone"and comp=="seasor" or player=="paper"and comp=="stone" or player=="seasor"and comp=="paper":
            print("yooo!! you won")
        elif player=="stone"and comp=="stone" or player=="paper"and comp=="paper"or player=="seasor"and comp=="seasor":
            print("tie baby")
        else:
            print("you loss baby")
    else:
        x=input("please enter again correct word like y or n bloody fool")
        continue
    x=input("pleae enter y to start or e to exit the game:")
    
print("the end")
