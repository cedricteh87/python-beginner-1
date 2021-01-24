# Hello World program in Python
BC = 100
BE = 90
M = 90

if not (BC <100) and BE ==100 and M ==100:
    print("World prize")

    
if BC > 80:
    print("BC-A")
elif BC > 70:
    print("BC-B")
elif BC > 60:
    print("BC-B")
elif BC > 50:
    print("BC-B")
else:
    print("BC-fail")
    
if BE > 80:
    print("BE-A")
elif BE > 70:
    print("BE-B")
elif BE > 60:
    print("BE-B")
elif BE > 50:
    print("BE-B")
else:
    print("BE-fail")
    
if M > 80:
    print("M-A")
elif M > 70:
    print("M-B")
elif M > 60:
    print("M-B")
elif M > 50:
    print("M-B")
else:
    print("M-fail")    
    
if BC ==100 or BE ==100 or M==100:
    if BC >80 and BE >80 and M >80:
        print("Accept")
    else:
        print("Reject")
        
        
    
