# Intro-t0-Webd
print("FIBONACCI NUMBER")

n=int(input("ENTER ANY NUMBER:"))
f1=0
f2=1
count=0
if n<=0:
    print("enter postive value")
elif n==1:
    print("sequence",n,":")
    print(f1)
else:
    print("sequence",n,":")
    while count < n:
        print(f1,end=',')
        fth=f1+f2
        f1=f2
        f2=fth
        count+=1