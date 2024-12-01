import time

def start_game():
    print("Welcome to 'Mystic Forest Adventure'!")
    print("You are an adventurer exploring a mysterious forest in search of a magical relic.")
    print("Make wise choices to survive and succeed!")
    input("\nPress Enter to begin your journey...")
    scene_1()

def scene_1():
    print("\nYou stand at the edge of a dark forest.")
    print("1. Enter the forest.")
    print("2. Walk around the forest.")
    print("3. Turn back and leave.")
    
    choice = input("What do you do? (1/2/3): ")
    
    if choice == "1":
        scene_2()
    elif choice == "2":
        print("\nYou find a warning sign that says 'Danger Ahead!'")
        print("You decide to leave. Game over!")
    elif choice == "3":
        print("\nYou turn back and head home safely. Game over!")
    else:
        print("\nInvalid choice! Try again.")
        scene_1()

def scene_2():
    print("\
