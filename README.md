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

