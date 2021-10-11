#Basic
for x in range(0, 151):
    print(x)

#Multiples of Five
y = 5
while y <= 1001:
    if (y % 5 ==0) :
      print(y)
    y = y + 1

#Counting, the Dojo Way
z = 1
while z <= 100:
    if(z % 10 ==0):
      print ("Coding Dojo")
    elif(z % 5 ==0) :
      print("Coding")
    else:
      print(z)
    z = z + 1

#Whoa. That Sucker's Huge
sum=0
for o in range(1, 500000, 2):
  sum=sum+o
print(sum)

#Countdown by Fours
for p in range(2018, 0, -4):
    print(p)

#Flexible Counter (optional)
lowNum=2
highNum=9
mult=3
for f in range(lowNum, highNum+1, 1):
    if (f%mult==0):
     print(f)
