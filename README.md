# riprequest
Similar to the Python request library, but for Reticulum

Useage example:
```python
from RIPRequest import RIPRequest

request = RIPRequest()
r = request.get("rip://2578107e805ce83655fd")
print(r.status)
print(r.type)
print("---")
print(r.body)
```

Outputs something like:
```
20
text/micron
---
>Hello World
This is my Webpage written in Micron!
```

