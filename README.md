
        num1 = int(input("Enter first integer: "))
        num2 = int(input("Enter second integer: "))
        op = input("Enter operator (+, -, *, /): ")

        if op == '+':
            result = num1 + num2
            print(f"{num1} + {num2} = {result}")
        elif op == '-':
            result = num1 - num2
            print(f"{num1} - {num2} = {result}")
        elif op == '*':
            result = num1 * num2
            print(f"{num1} * {num2} = {result}")
        elif op == '/':
            if num2 == 0:
                print("Division by zero is not allowed.")
            else:
                result = num1 // num2  # Integer division
                print(f"{num1} / {num2} = {result}")
        else:
            print("Invalid operator.")

    except ValueError:
        print("Invalid input. Please enter integers.")


