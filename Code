import time


def farm_house_bedroom():

    print("\nYou clothes on your back smelly and raggedy, so you decided to look for new clothes.")
    print(
        "You walk into the first bedroom and start sifting through the drawers.\nLuckly enough, you found a jacket that look like your size. You put down your gear to try it on. While your trying the jacket on, you hear a noise downstairs... A footstep ...(1 or 2)"
    )
    time.sleep(5)
    print("1). Keep looking for supplies Upstairs.")
    print("2). check out the noise downstairs?")

    # take input()
    answer = input(">")

    if answer == "1":
        # lead him to the game_over()
        game_over(
            " You decided to not waste any time, you ignored the noise.   \n.... You were eaten by the Dead......"
        )
    elif answer == "2":
        # the player is dead, call game_over() with "reason"
        game_over(
            "The only reason you have survived the Apocalypse is your cautiousness. You walk back into the hallway, where the upstairs staircase ends. Your calm sense of security is gone, the farmers son is standing right in front of you with a Glock .40 on his belt. He draws his weapon on you, his hand shaking so much, you are worried he will shoot you by accident. You shout \'Don't worry I'm a survivor'. He replies, \'your looting your house!'' You yell \'I didnt know anyone lived here!'. The farmers son crys out, \'you came here to steal from us'. You try and calm down the situation, \'I wont hurt you, just let me leav---'  \n.... You were shot......"
        )
    else:
        # game_over() with "reason"
        game_over("Go and learn how to type a number.")






def farm_house():

    print("\nYou decided to cautiously approach the farm house")
    print(
        "The house looks untouched by the Apocalypse.\nThe paint has but not a strach. The grass is perfectly cut, untainted by the acidic rain. Your suspicious, but your fatique and malnourishment surpasses petty suspiciousness. Your callused and bruised hand reaches for the bright white door handle. The handle twists and the door opens? (1 or 2)"
    )
    time.sleep(5)
    print("1). Go to the Kitchen and Scavenge for Food")
    print("2). Head Upstairs to look for new Clothes")

    # take input()
    answer = input(">")

    if answer == "1":
        # lead him to the hardware_store()
        farm_house_kitchen()
    elif answer == "2":
        # the player is dead, call game_over() with "reason"
        farm_house_bedroom()
            
    else:
        # game_over() with "reason"
        game_over("Go and learn how to type a number.")






def hardware_store():
    # some prompts
    # '\n' is to print the line in a new line
    print("\nYou made a break to the Hardware store")
    print(
        "You reach for the door handle, and in haste your body slams against the locked thin glass door.\nThe dead that fill the street, hear your clamouring. You get fed up, and smash your shoulder against the door, shattering the glass. (1 or 2)"
    )
    print(
        "\nYou step over the broken glass, to look for supply's. The shelf's of the hardware store are filled with ttoiletries, brooms, clothes hangers, drillbits, and other useless things... Ha you stumbled upon the tool section. Drills, socketwrenchs, hammers, Chisels, Punches, sledgehammers. You see all of these useful tools you could use as weapons.(1 or 2)"
    )
    print("But they won't all fit in your backpack")
    time.sleep(5)
    print(
        "1). Throw the sledgehammer over your shoulder, and walk back to the Grocery Store."
    )
    print(
        "2). Quickly grab the hammer and leave the store through the fire exit."
    )

    # take input()
    answer = input(">")

    if answer == "1":
        # lead him to the hardware_store()
        grocery_store()
    elif answer == "2":
        # the player is dead, call game_over() with "reason"
        side_road()
    else:
        # game_over() with "reason"
        game_over("Go and learn how to type a number.")





def the_street():

    print("You ran through the alley, to the street.")
    print(
        "\nBefore you even can think, the smell of the living dead overtakes you.\nThere are zombies to the left and right of you. You can't even count how many there are. You immediately reach for your double barrel and fire...Nothing, you forget the sawed-off shotgun in your hands is out of ammunition What would you do? (1 or 2)"
    )
    time.sleep(5)
    print("1). Make a break for the Hardware store.")
    print("2). Use the shotgun as a Melee Weapon and fight like hell.")

    # take input()
    answer = input(">")

    if answer == "1":
        # lead him to the hardware_store()
        hardware_store()
    elif answer == "2":
        # the player is dead, call game_over() with "reason"
        game_over(
            " You thrusted your shotgun right into the jaw of a zombie, the zombie collasped to the ground. While you were focused on killing one zombie. Another grabbed you from behind. Throwing you off balance.... You were eaten by the Dead......"
        )
    else:
        # game_over() with "reason"
        game_over("Go and learn how to type a number.")


def town_ravine():
    # some prompts
    # '\n' is to print the line in a new line
    print(
        "\nYou have left the grocery store to fin yourself in a forest/ravine."
    )
    print(
        "You keep away from the safety of the grocery store through the forest.\nThere stray zombies here and there, but you can aviod them. The dense bush of a ravine is slowly starting to clear up. You approach an opening into a farmers field. You field is dark fertile brown. It looks like the field had been tended reacently. You stop looking at the ground and look up, there is a old farm house ahead. (1 or 2)"
    )
    time.sleep(5)
    print("1). Cautiously Approach the Farmhouse")
    print("2). Go back to the Grocery store.")

    # take input()
    answer = input(">")

    if answer == "1":
        # lead him to the hardware_store()
        farm_house()
    elif answer == "2":
        # the player is dead, call game_over() with "reason"
        grocery_store()
    else:
        # game_over() with "reason"
        game_over("Go and learn how to type a number.")






def the_back_alley():
    print("\nYou climbed down the fire escape. ")
    print("The fire escape is located at the back alley of the grocery store.")
    print(
        "The back alley has a pathway into the small town ravine, and a clear passage to the street (1 or 2)"
    )
    time.sleep(5)
    print("1). Run to the town ravine.")
    print("2). Run to the street.")
    print("")

    answer = input(">")

    if answer == "1":
        #go to the town ravine
        town_ravine()
    elif answer == "2":
        print("\nUnfinished Game text")
        the_street()
    else:
        # else call game_over() function with the "reason" argument
        game_over("Don't you know how to type a number?")


def grocery_store():
    # some prompts
    # '\n' is to print the line in a new line
    print("\nYou decided to play it safe and go back into the store.")
    print(
        "The bottom of the staircase, leads to the storage supply room at the back of the store.\nYour stomach growls from hunger. And the thought of consuming canned corn or canned pork is overtaking. (1 or 2)"
    )
    time.sleep(5)
    print("1). Are you going to check the store for food supply's")
    print(
        "2). Slip out of the loading dock; leaving the store. Which Leads to the Ravine behind the store."
    )

    # take input()
    answer = input(">")

    if answer == "1":
        # lead him to the hardware_store()
        game_over(
            "\nYou walked straight to the canned food aisle, your hungry eyes scanned the shelf's horizon. Nothing... Pure Emptyness .. It has been two years since the store was restocked. You kick the shelf in frustration... You hear the moans .. The store is full of dead looters, every aisle shakes will the sound of cold groans. You are trapped, with no food, weapon or ammo. "
        )
    elif answer == "2":
        # the player is dead, call game_over() with "reason"
        town_ravine()
    else:
        # game_over() with "reason"
        game_over("Go and learn how to type a number.")


def play_again():
    print("\nDo you want to play again? (y or n)")

    answer = input(">").lower()

    if "y" in answer:
        # if player typed "yes" or "y" start the game from the beginning
        start()
    else:
        # if user types anything besides "yes" or "y", exit() the program
        exit()





# game_over function accepts an argument called "reason"
def game_over(reason):
    # print the "reason" in a new line (\n)
    print("\n" + reason)
    print("You did not live to fight another day....")
    # ask player to play again or not by activating play_again() function
    play_again()




def start():
    print("--The Dead Below--")
    print()
    print()
    print("...")
    print(
        "\nYou are on the roof of a Grocery Store. You have not slept in two days, ate in two weeks, or showered in two years. You are one, if not the only survivor of the ...Zombie Apocalypse... "
    )
    print(
        "\nYour sawed-off shotgun is empty, the Taurus 9mm on your belt has a broken firing pin. All you have is your unoccupied backpack, and a sense of hope."
    )
    print(
        "\nYou can barely think about the situation of your supply's, over the utter, horific, and atrocious sound of the dead below. "
    )
    print(
        "\nThere is a fire escape to your left which leads to the back alley, and a staircase back inside the store. which one do you take? (1 or 2)"
    )
    print()
    time.sleep(7)
    print("1). Run to the back_alley.")
    print("2). Go back inside the Grocery store.")

    answer = input(">").lower()

    if answer == "1":
        # this leads the player to the back alley()
        the_back_alley()
    elif answer == "2":
        # this leads the player inside the grocery store
        grocery_store()
    else:
        # game_over() with "reason"
        game_over("Go and learn how to type a number.")


start()
