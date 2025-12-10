name=input("Enter Students name:")
roll=int(input("Enter Students rollno.:"))
course=input("Enter course name:")
print("Enter marks for 100:")
m1=int(input("Subject 1:"))
m2=int(input("Subject 2:"))
m3=int(input("Subject 3:"))
m4=int(input("Subject 4:"))
m5=int(input("Subject 5:"))
total=m1+m2+m3+m4+m5
percent=total/5
print("STUDENT DETAILS")
print("------------------------------")
print("NAME:",name)
print("ROLL NO:",roll)
print("COURSE:",course)
    
if percent>=90:
    print("GRADE:A1")
elif percent<=80 and percent>=75:
    print("GRADE:A2")
elif percent<=75 and percent>=65:
    prnt("GRADE:B1")
elif percent<=65 and percent>=50:
    print("GRADE:B2")
else:
    print("FAIL")



OUTPUT:
Enter Students name:Maddison
Enter Students rollno.:195
Enter course name:Computer Science
Enter marks for 100:
Subject 1:90
Subject 2:85
Subject 3:89
Subject 4:93
Subject 5:96
STUDENT DETAILS
------------------------------
NAME: Maddison
ROLL NO: 195
COURSE: Computer Science
GRADE:A1
