# BMI-Calculator

name= input("enter your name: ")
weight= int(input("enter your weight in kilos: "))

height= int(input("enter your height in inches: "))

BMI= (weight*1550.0031)/(height * height)
print(BMI)

if BMI>0:
    if(BMI<18.5):
        print(name+",You are underweight. eat something !")
    elif (BMI<=24.9):
        print(name+",You are normal weight. wanna go on a date?")
    elif (BMI<29.9):
        print(name+",You are overweight. Lift some weigths!")
    elif (BMI<34.9):
        print(name+",You are obese. Let your family eat something too!")
    elif (BMI<39.9):
        print(name+",You are severly obese. I know 3 fat people and your are 2 of them haha")
    elif (BMI>=40):
        print(name+",You are morbidly obese. Bro you are cooked")
    else:
        print(name+",Enter Valid inputs")

input() 



