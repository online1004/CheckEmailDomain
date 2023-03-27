# checkemail
Do you need to verify the domain used in the email?

Use the checkemail module to work more comfortably

Developed by online1004 (c) 2023

# Examples of How To Use
```python
import checkemail 

# With a String
checkemail.checkDomain('gmail.com', 'online1004@gmail.com') # (True, 'Vaild Domain')
checkemail.checkDomain('naver.com', 'online1004@online1004.xyz') # (False, 'Invaild Domain')

# With a List
checkemail.checkDomain(['gmail.com', 'naver.com', 'hotmail.com'], 'online1004@hotmail.com') # (True, 'Vaild Domain')
checkemail.checkDomain(['gmail.com', 'naver.com', 'hotmail.com'], 'online1004@online1004.xyz') # (False, 'Invaild Domain')
```

https://pypi.org/project/checkemail/
