# ass-1-12-02-22
#Write a program to prepare super market bill?
print('enter any 5 values')
n=int(input())
disc=0
tax=0
if n>5000:
    disc=n*(10/100)
elif n>3000:
    disc=n*(8/100)
elif n>2000:
    disc=n*(5/100)
elif n>1000:
    disc=n*(3/100)
if n>3000:
    tax=n*(10/100)
else:
    tax=n*(18/100)
print('discount is :',disc)
print('tax is:',tax)
n-=1

output:
enter any 5 values
1000
discount is: 0
tax is: 180.0
