# PYTHON11
IMPORT DATETIME FROM DIFFERENT REGIONS


import pytz
from datetime import datetime
a=pytz.timezone("Asia/Kolkata")
b=datetime.now(a)
print(b)
