# Python-1
A library charges a fine for every book returned late. For first 5 days the fine is 50 paisa, for 6- 10 days fine is one rupee and above 10 days fine is 5 rupees. If you return the book after 30 days your membership will be cancelled.
d=int(input("Enter Number of days:"))
fine=0
if(d<=5):
       fine=d*0.50
       print("Fine :",float(fine))
elif(d>5 and d<=10):
      i=d-5
      fine=(i*1)+(5*0.5)
      print("Fine : ",float(fine))
elif(d>10 and d<=30):
      i=d-10
      fine=(i*5)+(5*0.5)+(5*1)
      print("Fine :",float(fine))
else:
      i=d-10
      fine=(i*5)+(5*0.5)+(5*1)
      print("Your Membership is cancelled")
      print("Fine amount (Rs): ",float(fine))
Output:
Enter Number of days: 14
Fine amount (Rs): 27.5

