# Combo Generator Code

```
import os, random
gppass = "017"
gp = "88017"
for i in range (10) :
  randomn = random.randint(11111111,99999999)
  rannum = str (randomn)
  number = gp + rannum
  password = gppass + rannum
  open ("combo.txt" ,"a").write("\n"+number + ":" + password )
 
```
