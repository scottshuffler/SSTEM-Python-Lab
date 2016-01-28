# SSTEM-Python-Lab

You can do this on your local machine, student, or the Raspberry Pi.

Be sure to be using Python3

Here is the code we wrote during out meeting:

``` python

class hello_class():
    def __init__(self):
        self.user_string = ''

    def hello_world(self):
        print('hello world')

    def main(self):
        while True:
            arg = input('-> ')
            if (arg == 'quit'):
                print(self.user_string)
                break
            else:
                self.user_string += arg


if __name__ == '__main__':
    hc = hello_class()
    hc.hello_world()
    hc.main()
```

Modify the class above to create a calculator 
 - Display a message before you ask for input, for example: Simple Calculator 1.0
 - Prompt the user three times (first number, operator, and second number)
 - Create four new functions (Multiply, divide, add, and subtract)
 - Evaluate the operator and call the appropriate function using the two numbers as parameters, for example: multi(self, l_param, r_param)
 - Display the result with the full equation, for example: 2 + 3 = 5
