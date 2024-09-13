while True:
  a=int(input("enter the starting no."))
  b=int(input("enter the ending no."))
  c=int(input("enter the updating no."))
  d=input("enter the h or v ")
  e=input("enter the r or f ")
  if(e=="f"):
       for i in range(a,b,c):
           if(d=="h"):
               print(i,end="  ")
           elif(d=="v"):
               print(i)
           else:
               print("error")
  elif(e=="r"):
        for i in range(b,a-1,-c):
         if(d=="h"):
             print(i,end="  ")
         elif(d=="v"):
             print(i)
         else:
             print("error")  