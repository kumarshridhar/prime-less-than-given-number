# prime-less-than-given-number
flag=True
  for i in range(2,n):
    if(n%i==0):
      print('not prime')
      flag=False
      break
  if(flag):
    print('prime')
