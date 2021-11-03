# helloworld
Just a start

#Stickman with stairs code in python.

n=int(input("Enter the number of stairs: "))
nf=n*5+7       # nf=number of stars on the floor

for stair_number in range(n):
    
    spaces1= (n-stair_number-1)*5+1  #indentation for stickman
    spaces2=stair_number*5           #indentation for stickman's head part
    spaces3=stair_number*5+5         #indentation for stickman's body and legs part
    for i in range(spaces1):
        print(' ',end='')
    print (" o  ******",end='')
    
    for i in range(spaces2):
         print(' ',end='')
    print('*')
        
    for i in range(spaces1):
        print(' ',end='')
    print ("/|\ *",end='')
    
    for i in range(spaces3):
         print(' ',end='')
    print('*')
    
    for i in range(spaces1):
        print(' ', end='')
    print ("/ \ *",end='')
    
    for i in range(spaces3):
         print(' ',end='')
    print('*')
    
    
for b in range(nf):               #stars on the floor
    print('*', end=(''))
