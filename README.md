# shalini077
def add(x, y):
    return x + y

def sub(x,y):
    return x - y

def mul(x,y):
    return x * y

def div(x,y):
    return x/y

print('select option:')
print('1.addition')
print('2.substraction')
print('3.multiplication')
print('4.division')

choice = input('enter your choice letter(1/2/3/4:)')
num1 = int(input('enter your 1st number'))
num2 = int(input('enter your 2nd choice'))

if choice == '1':
    print(add(num1,num2))
elif choice == '2':
    print(sub(num1,num2))
elif choice == '3':
    print(mul(num1,num2))
elif choice == '4':
    print(div(num1,num2))
else:
    print('invalid input')
