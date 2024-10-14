import random
def input_computer_choice():
    return random.choice(["rock","paper","scissors"])
def input_user_choice():
    user_input= input("Enter rock, paper or scissors:").lower()
    while user_input not in ["rock","paper", "scissors"]:
        print("Invalid choice, please try again")
        user_input=input("Enter rock, paper or scissors:").lower
    return user_input
def winner(user_choice,computer_choice):
    if user_choice==computer_choice:
        print("It's a draw!")
    elif (user_choice=="rock" and computer_choice=="scissors") or (user_choice=="scissors" and computer_choice=="paper")  or  (user_choice=="paper" and computer_choice=="rock"):
        print("You win!")
    else:
        print("The computer wins")
def play():
    print("Welcome to rock, paper, scissors!")
    while True:
        user_choice= input_user_choice()
        computer_choice= input_computer_choice()
        print(f'You chose {user_choice}')
        print(f'The computer chose {computer_choice}')
        result= winner(user_choice,computer_choice)
        return result

        play_again= input("Do you want to play again? Press Y for yes, N for no.").lower()
        if play_again=="n":
            print("Thanks for playing!")
            break
if __name__=="__main__":
    play()
            
