# march-5th
def sumEven(n):
    if n%2 == 1:
        n -=1
    s = 0
    for i in range(n, 0, -2):
        s += i
    return s
   
   
print(sumEven(7))
#########################################
#def calculateBMI(w, h):
#    return w / (h * h)
#
#result = calculateBMI(50, 1.72)
#print("Your weight and height is", result)
#########################################
#def count_down_up(n):
    #or i in range(n,0,-1):
        #print (i, "...", end =  " ")
    #for i in range(0,4):
        #print (i, "...", end =  " ")
#count_down_up(3)
