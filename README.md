# python-caculater
I maded a working caculater in python, making me one step closer to my goal to make a fully functional game that makes a hit 
sign = input("which sign will you use */+-   ")

if sign == "+" or sign ==  "-" or  sign == "/" or sign == "*":
    print("prossesing...")
else:
    quit()
import time

time.sleep(2)

first_num = input("what is the fisrt number you will input   ")
print("prossesing...")
import time

time.sleep(2)
second_num = input("what is the second number you will input   ")
print("prossesing...")
import time

time.sleep(2)
if sign == "+":
     print(float(first_num) + float(second_num))

if sign == "-":
    print(float(first_num) - float(second_num))

if sign == "*" :
    print(float(first_num) * float(second_num))

if sign == "/" :
    print(float(first_num) / float(second_num))
