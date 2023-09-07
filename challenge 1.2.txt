year=int(input("Enter the leap year:"))
year = 2000
if(year%4==0 and year%400==0) or year%100==0:
     print(year,"is a leap year")
else:
    print(year,"is not a leap year")