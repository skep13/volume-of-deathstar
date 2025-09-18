# volume-of-deathstar

import math 
d=160
r=d/2
pi=math.pi
volume=4/3*pi*r**3
print("the volume of a complete death star is ", volume, "cubic kilometres")
dhollow=40
rhollow=dhollow/2
vhollow=(1/3)*4/3*pi*rhollow**3
print("the hollow volume is ", vhollow, "cubic kilometres")
print("death star volume is ", volume-vhollow, "cubic kilometres"
