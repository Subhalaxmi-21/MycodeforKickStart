def calc(n,s,t,i):
    s=list(s)
    sum=0

    for i in range(len(s)):
        left = 0
        right=0
    
        if s[i]=='0':
       
            while right!=1:
                left+=1
                if i-left>=0 and i-left<len(s):
                    if s[i-left]=='1':
                        
                        right=1
                        sum+=left
                        break
                if i+left>=0 and i+left<len(s) :
                    if s[i+left]=='1':
                       
                        right = 1
                        sum+=left
                        break
    return sum



t= int(input())
for i in range(t):
    n=int(input())
    s=input()
    res=calc(n,s,t,i)
    print(f'Case #{i+1}: {res}')
