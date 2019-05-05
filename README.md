# Assignment-1-task-1
# question 1
sed -n 's/Huck/HucK/p' twain.txt
# question 3
# -*- coding: UTF-8 -*-
year = int(input("input a year："))
if (year % 4) == 0 and (year % 100) != 0 or (year % 400) == 0:
    print("{0}is a leap year".format(year))
else:
    print("{0}is not a leap year".format(year))
# question 4
import stdio
import sys
import random

a = int(sys.argv[1])
b = int(sys.argv[2])

stdio.writeln(random.randrange(a,b+1))
# question 5
import stdio
import sys

m = int(sys.argv[1])
d = int(sys.argv[2])

if (m == 3 and d >= 18 and d <=31 ) or ( m == 6 and d >= 1 and d <=30) or (m > 3 and m < 6 and d >=1 and d <=30) or (m == 5 and d ==31):
  stdio.writeln('True')
# question 6
amt = 10000
int = 3.5
years = 7

future_value  = amt*((1+(0.01*int)) ** years)
print(round(future_value,2))
