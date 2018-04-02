# Upper-or-Lower
Write a Python function that accepts a string and calculates the number of upper case letters and lower case letters.

upper=0
lower=0
def up_low(s):
    global upper
    global lower
    for i,c in enumerate(s):
        if c in ['a','b','c','d','e','f','g','h','i','j','k','l','m','n','o','p','q','r','s','t','u','v','w','x','y','z']:
            lower += 1
        elif c in ['A','B','C','D','E','F','G','H','I','J','K','L','M','N','O','P','Q','R','S','T','U','V','W','X','Y','Z']:
            upper +=1
        else:
            pass
    print('No. of Upper case characters : '+ str(upper))
    print('No. of lower case characters : '+ str(lower))
