# alarm-clock
import os
import datetime
import time
from datetime import date

c,b,a = input("ENTER THE DATE = ").split("/")
hr,min,sec = input("Enter the Time = ").split(":")
shedule_date = datetime.date(int(a),int(b),int(c))
n=1
while n>0:
    if time.localtime().tm_hour==int(hr) and time.localtime().tm_min==int(min) and time.localtime().tm_sec==int(sec) and datetime.date.today()==shedule_date:
     os.startfile(r'C:\Users\adhij\Desktop\G.O.A.T. - (Raag.Fm).mp3')
     break
    else:
        n+=1
