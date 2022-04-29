# prime-less-than-given-number
n=int(input('enter number:'))
for i in range(2,n):
  flag=True
  for j in range(2,i):
    if(i%j==0):
      flag=False
      break
  if(flag):
    print(i,end=' ')
