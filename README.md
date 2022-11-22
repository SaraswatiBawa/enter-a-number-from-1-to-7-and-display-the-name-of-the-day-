# enter-a-number-from-1-to-7-and-display-the-name-of-the-day-

day=int(input("Enter the following number for the day: 1,2,3,4,5,6,7\n"))

if(day==1):
    print("Sunday")
elif(day==2):
    print("Monday")
elif(day==3):
    print("Tuesday")
elif(day==4):
    print("Wednesday")
elif(day==5):
    print("Thursday")
elif(day==6):
    print("Friday")
elif(day==7):
    print("Saturday")
else:
    print("Enter Input Between 1 to 7")
