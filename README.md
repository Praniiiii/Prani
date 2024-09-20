#Prani
#a=10
#print(id(a))

#a = 10
#print(bool(a))

#a = 10
#print(complex(a))

#a="pranita"
#b=a[0]
#print(b)

#a="pranita"
#b=a[1:4:2]
#print(b)

#a="swapnodaya"
#b=a[0:10:2]ittu
#print(b)

#a="malayalam"
#b=a[-1:-10:-1]
#print(b)

#a="malayalam"
#b=a[-10::-2]
#print(b)

#c=[2,3,'hello',1+2j]
#print(c[2][0:2])

#d=[2,'hi',[10,20,30],50]
#print(d[2][2])

"""insta=input("enter your userid")
password=input("enter your password")
if insta=="prani":
    print("login successful")
    if password==8001:
        print("password is correct")
    else:
        print("please enter the correct password")
else:
    print("invalid userid and password")"""
from itertools import count

"""avg=int(input("Enter the grade"))
if(avg>=90 and avg<=100):
    print("Grade: A")
elif(avg>=80&avg<90):
    print("Grade: B")
elif(avg>=70&avg<80):
    print("Grade: C")
elif(avg>=60&avg<70):
    print("Grade: D")
else:
    print("Grade: F")"""

#even no
#i=0
#while i<=10:
    #if i%2==0:
      #  print(i)
    #i=i+1

#odd no
#i=0
#while i<= 10:
    #if  i %2!=0:
    #    print(i)
   # i = i + 1

#sum of even numbers upto 10
"""sum=0
i=0
while i<=10:
    if i%2==0:
        sum=sum+i
    i=i+1
print(sum)"""

#single or multivalued
#a=[1,2,3,4]
#i=0
#while i<len(a):
    #if type(a[i])in (int,bool,float,complex):
     #   print("single valued")
    #else:
     #   print("multivalued")
    #i=i+1

#even index characters
#b="swapnodaya"
#i=0
#while i<len(b):
    #if i%2==0:
     #   print(b[i])
    #i=i+1

# WRITE A PROGRAM TO GET THE TOTAL NO. OF ALPHABETS, NO. AND SPECIAL CHARACTERS IN A GIVEN STRING
"""a='2ew24cs040#'
num=""
alpha=""
special=""
i=0
num_count=0
alpha_count=0
special_count=0
while i<len(a):
    if '0'<=a[i]<='9':
        num=num+a[i]
        num_count+=1
    elif 'a'<=a[i]<='z' or 'A'<=a[i]<='Z':
        alpha=alpha+a[i]
        alpha_count+=1
    else:
        special=special+a[i]
        special_count+=1
    i+=1
print("numbers:",num_count)
print("alphabets:",alpha_count)
print("special character:",special_count)"""

#extract only special characters present inside a given string
"""b="swapnodaya##"
sp=""
i=0
while i<len(b):
    if not ('0'<=b[i]<='9' or 'a'<=b[i]<='z' or 'A'<=b[i]<='Z'):
        print(b[i])
    i+=1"""

"""b="swapnodaya##"
sp=""
i=0
while i<len(b):
    if not ('0'<=b[i]<='9' or 'a'<=b[i]<='z' or 'A'<=b[i]<='Z'):
        print(b[i])
    i+=1"""

#c=['hi','90','hello',90]
#output d=['hi','90','hello']

"""c=['hi','90','hello',90]
c.pop()
print(c)"""

#e=ok!bye output=2
"""e="ok!bye"
c=0
i=0
while i<len(e):
    if e[i] in ('a','e','i','o','u'):
        c=c+1
    i+=1
print(c)"""

#5
"""a="python"
print(a[::-1])"""
#OR
"""a = "python"
reversed_a = ''
for char in a:
    reversed_a = char + reversed_a
print(reversed_a)"""

"""d="Hi"
e=["Python","Sql"]
b={}
i=0
while i<len(d) and i<len(e):
    b[d[i]]=e[i]
    i += 1
print(b)"""

"""a=['python','sql']
i=0
c={}
while i<len(a):
    c[a[i]]=len(a[i])
    i+=1
print(c)"""

"""n=6
i=1
sum=0
while i<n:
    if n%i==0:
        sum=sum+i
    i=i+1
if sum==n:
    print("perfect number")
else:
    print("not perfect number")"""

"""d=['python','sql']
e=[]
for i in d:
    c=0
    for j in i:
        c=c+1
    e=e+[c]
print(e)"""

"""d=["hello","hi"]
e=[]
for i in d:
    c=0
    for j in i:
        if j  in ('aeiouAEIOU'):
            c=c+1
    e=e+[c]
print(e)"""

"""d=["hello","hi"]
e=[]
for i in d:
    c=0
    for j in i:
        if j  not in ('aeiouAEIOU'):
            c=c+1
    e=e+[c]
print(e)"""

"""d=["python","workshop"]
b=[]
for i in d:
    sum=0
    for j in range(len(i)):
        if j%2==0:
            sum=sum+1
    b=b+[sum]
print(b)"""

"""d="aabbcc"
b=''
for i in d:
    #if i not in b:
        c=0
        for j in d:
            if i==j:
                c=c+1
        b=b+i+str(c)
print(b)"""

"""d="aabbcc"
b=''
e=''
f=''
for i in d:
    if i not in b:
        c=0
        for j in d:
            if i==j:
                c=c+1
        b=b+i
        e=e+str(c)
        f=b+e
print(f)"""

"""def add(a,b):
    return a+b
print(add(2,3))"""



"""def even(a):
    if a%2==0:
        print("even")
    else:
        print("not even")
even(3)"""

# TO FIND A FACTORIAL
"""def fact(a):
    if a==1:
        return 1
    else:
        return a*fact(a-1)
print(fact(3))"""

"""def fname(*a):
    print("project name")
    print("project number")
fname('prani',99)"""

"""def d(a,b,c):
    print(a,b,c)
d(*{'H':1,'B':2,'E':3})"""

#variable argument
"""def c(*a,**b):
    print(a)
    print(b)
c(1,2,3,'h'=2,'e'=3)"""
#**=keyword argument

