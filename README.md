# patterns-17
n=int(input())
for i in range(n):
  for j in range(n):
    if i==0 or i==(n-1) or j==0 or j==(n-1):
      print(f"*", end=" ")
    else:
      print(" ",end=" ")
  print()
