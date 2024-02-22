# GK - Get Key

#### Works both in Windows and Linux (tested on Ubuntu)

It works like that

```
import gk

key = gk.getkeyInASCII()
```

Key will be the represenation of key that was hit in ASCII code

## You can test it by creating simple code like this 

```
import gk

while True:
    key = gk.getkeyInASCII()
        
    print(f"Key that was pressed = {key}")
```
