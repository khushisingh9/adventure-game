# adventure-game

name=input("Enter your name :").upper()
print("Welcome",name,"to adventure game")

answer=input("You came across a adventurous road which it will break anytime,you have to go on left or right")
if answer=="left":
    answer=input("you came across a river,you can walk around it or swim across(walk/swim)")
    
    if answer=="swim":
        print("you came across and eaten by a crocodile")
    elif answer=="walk":
        print("you kept walking and ran out of water and loose")
    else:
          print("invalid option")
elif answer=="right":
      answer=input("you came across a stranger(talk/ignore)")
      if answer=="talk":
        print("he gave you gold and you won")
      elif answer=="ignore":
        print("he got ofended and you lost")
      else:
          print("invalid option")
