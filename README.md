# PYTHON11
IMPORT DATETIME FROM DIFFERENT REGIONS


import pytz
from datetime import datetime
a=pytz.timezone("Asia/Kolkata")
b=datetime.now(a)
print(b)
# Python 12
names = ("Sai","Rizwan","Nanda","Laxshmi","Hero")
marks = (75,80,35,47,83)
pos=1
for i in range(5):
    if marks[i]>50:
        print("{}.{} has scored {}%".format (pos,names[i],marks[i]))
        pos = pos+1

# Python 13
a=(2,333333333,4,5)
b=(3,4444,5,6)
print(a,b)

# Python 14
a=[2,4,7,8,9,6]
b=[3,7,7,9,6,7]
a.append({2,4})
b.append({3,7,7,9,6})
print(a)

# Python 15
a=[[" " for i in range(11)] for i in range(10)]

for i in range(10):
    for j in range(11):
        if j==0 or j==10:
            a[i][j]="*"
        if i==j and i<=5:
            a[i][j]="*"
        if i+j==10 and j>5:
            a[i][j]="*"
for i in range(10):
    for j in range(11):
        print(a[i][j],end="")
    print()

# Python 16
class abc:
    def set_dim(self):
        x = int(input("Enter the num1: "))
        y = int(input("Enter the num2: "))

        self.a = x
        self.b = y

    def display(self):
        print(self.a + self.b)


a1 = abc()      
a1.set_dim()   
a1.display()  

# Python 17

d={'A':1,'B':10,'C':100,'D':1000,'E':100000}
s="ABCDEF"

sum = 0
for i in s:
    if i in d.keys():
        sum = sum+d[i]
        print(sum)

# Python 18
