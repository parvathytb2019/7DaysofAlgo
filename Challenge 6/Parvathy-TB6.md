# Code
```python
def leapYear(days,hours,day):
    if hours == 0:
        return("Your planet will have {} days in a year and no leap year".format(days))
    else:
        leap_year = day//hours
        return("Your plane will have {} days in a year and a leap year every {} years".format(days,leap_year))
print("How much time does your planet take to complete a revolution around your star or blackhole?")
days = int(input("Days : "))
hours = int(input("Hours : "))
print("How many hours do you have a day?")
day = int(input())
print(leapYear(days,hours,day))
```
# Explanation
1. Input the number of days, hours, and hours in a day
2. pass these parameters to the function `leapYear()`
3. if hours is zero there is no leap years in the planet
4. Otherwise there will be leap years
