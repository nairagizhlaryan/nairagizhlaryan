def   isPrime  (n):
k=2
while k*k<=n   &  n%k  !=0:
k+=1
return (k*k>n)
if k*k>n:
return True 
else:
return false  
