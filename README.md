## checkemail
Do you need to verify the domain used in the email?

Use the checkemail module to work more comfortably

Developed by online1004 (c) 2023

## Examples of How To Use
```python
import checkemail as ce 

# With a String
rs1 = ce.emailInfo('gmail.com', 'online1004@gmail.com').checkDomain() # (True, 'Vaild Domain')
rs2 = ce.emailInfo('naver.com', 'online1004@online1004.xyz').checkDomain() # (False, 'Invaild Domain')

# With a List
rs3 = ce.emailInfo(['gmail.com', 'naver.com', 'hotmail.com'], 'online1004@hotmail.com').checkDomain() # (True, 'Vaild Domain')
rs4 = ce.emailInfo(['gmail.com', 'naver.com', 'hotmail.com'], 'online1004@online1004.xyz').checkDomain() # (False, 'Invaild Domain')

print(f'{rs1}\n{rs2}\n{rs3}\n{rs4}')
```

[Pypi Module](https://pypi.org/project/checkemail/)
