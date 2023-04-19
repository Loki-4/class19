# class19
pascal case:each word starting should be capital
ex:: MyNameIs="loki"
camel case::start word start with small rem wil be capital
ex::myNameIs="loki"
snake case:all words start with small and seperated by underscore
ex::my_name_is="loki"

#a,b,c=1,2,3
a=b=c=1
patterns
---------
for i in range(1,6):
  for j range(1,i+1):
    print(j,end="")
  print()
  
1
12
123
1234
12345

for i in range(1,6):
  for j range(1,i+1):
    print(i,end="")
  print()
1
22
333
4444
55555

#PALINDROME
--------------
str=input()
if(str==str[::-1])
  print("palindrome")
else:
  print("not palindrome")
  
  num=int(input())
  temp=num
  rev=0
  while(num != 0):
     rem=num%10
     rev=rev*10+rem
     num=num//10
  if temp==rev:
     print("palindrome")
else:
  print("not palindrome")
  
  // floor division----->return integer
  / ------->return float
  #armstrong
  a=int(input("enter: "))
b=len(str(a))
temp=a
print("power",b)
sum=0
while(a!=0):
    rem=a%10
    sum+=pow(rem,b)
    a=a//10
if temp==sum:
    print("armstrong")
else:
    print("not armstrong")
output
-------
enter: 153
power 3
armstrong
