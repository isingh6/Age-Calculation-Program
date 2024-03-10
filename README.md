main_input = input("Enter 1 if you want to check current data:\nEnter 2 if you want to see your future age:\n")
if main_input == '1':
    user_input = input(("Enter your Age or Year of birth: "))
    user_input = int(user_input)
    if user_input > 90 and user_input < 110:
        print(f"Your Year of birth is {user_input} You are oldest person alive")
        print(f"Your Year of birth is {user_input} You are oldest person alive")
    elif user_input <= 90:
        print(f"Your Age is {user_input} and you will turn 100 in {100-user_input} years.")
    elif user_input > 2022:
        print(f"Your Year of birth is {user_input} You are not born yet!")
    elif user_input > 1940:
        print(f"Your Year of birth is {user_input} and you will turn 100 years in {100-(2022-user_input)} years")
    else:
        print(f"This is not a valid age or year of birth")
elif main_input == '2':
    user_input2 = input(("Enter your Year of birth: "))
    user_input2future = input(("Enter future Year of birth: "))
    user_input2 = int(user_input2)
    user_input2future = int(user_input2future)
    if user_input2 > 2022:
        print(f"Your Year of birth is {user_input2} You are not born yet!")
    elif user_input2 < 1940:
        print(f"Your Year of birth is {user_input2} You are oldest person alive")
    print(f"Your age is {(2022-user_input2)} and your age in year {(user_input2future)} will be {(user_input2future)-(user_input2)}")
