# MGK - My Key Input

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
    key = 0

    while key == 0:
        key = gk.getkeyInASCII()
        key = list(key)
        key = key[0]
        
    print(f"Key that was pressed = {key}")
```