Password generator- PYTHON

def main():
    # Ask the user to set the password
    password = input("Set your password: ")

    # Ask the user to enter the password
    while True:
        user_password = input("Enter the password: ")

        # Check if the entered password matches the initially set password
        if user_password == password:
            print("Password accepted!")
            break  # Exit the loop if the password is correct
        else:
            print("Incorrect password. Please try again.")

if __name__ == "__main__":
    main()
