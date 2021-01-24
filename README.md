# school-marking-system-test
#a program that input students marks and total marks to output percentage marks and grade

studentmarks = int(input("enter students marks"))
totalmarks=int(input("input total marks"))
percentagemarks = int(studentmarks/totalmarks * 100)
   
print ((percentagemarks),"%")
if percentagemarks>= 80:
    print ("grade is A")
elif percentagemarks>= 70:
    print ("your grade is B")
elif percentagemarks >= 60:
    print ("your grade is C")
else:
    print("you have failed!,try harder next time!")
