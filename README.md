import math
s=0
n=2
epsilon=0.001
y=math.cos(n*x)/((n-1)(n+1))
if y<=0.001:
  s=s+y
  n+=2
print(s)
