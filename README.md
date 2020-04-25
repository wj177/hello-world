# hello-world
import numpy as np
import random
c=np.array(range(1,6),dtype=bool)
print(c,c.dtype)
c1=c.astype(int)
print(c1)
b=np.array([random.random()for i in range(10)])
print(b)
b1=np.round(b,2)
print(b1)
