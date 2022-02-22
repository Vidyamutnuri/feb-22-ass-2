# feb-22-ass-2
Assignment-2
n=int(input('enter n value:'))
for i in range(1,n+1):
    for j in range(1,i+1):
        print(j,end=" ")
    print('\n')
for i in range(1,n+1):
    for j in range(n,i,-1):
        print(n-j+1,end=" ")
    print('\n')
    
    Output:
    1 
    1 2
    1 2 3
    1 2 3 4
    1 2 3 
    1 2 
    1
    
    
