# kargah-camputer
a=float(input())
b=float(input())
BMI=a/b**2
if(BMI<19):
    print('underweight')
if(25>BMI>=19):
    print('normal')
if(30>BMI>=25):
    print('overweight')
if(BMI>=30):
    print('obese')