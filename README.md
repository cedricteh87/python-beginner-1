#i=i+1 simplified to i +=1
#i=i-1 simplified to i-=1
#can add string by combining string + integer


i=0
print("yo",i)
print("yo" + str(i))
i +=1
print("yo",i)
print("yo" + str(i))
i +=1
print("yo",i)
print("yo" + str(i))
i +=1

print(i)
print(type(i))
print(i+i)
print("after 3 years 2 of them added up is", i+i)
print("if 3 of them", i**2)

#for loop , for i in range(0,10); print("Hello World")
#while loop, i =0; while(i<10): print("Hello");i+=1

for i in range(0,3):
    print("hello")
    
i=0
while(i<10):
    print("Yolo"+str(i))
    i+=1
    
#Math: f(x)=x+3,    Python: def f(x): return x+3
def f(x):
    return x+3
    
print( f(5))  
