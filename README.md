# Code-Golf
https://codegolf.stackexchange.com/

## I'm a palindrome. Are you?
https://codegolf.stackexchange.com/questions/110582/im-a-palindrome-are-you
### Python 3 - 57 bytes
```
S=input()#
print(S[::-1]==S)#)S==]1-::[S(tnirp
#)(tupni=S
```

## All colorings of a 3x3 grid
https://codegolf.stackexchange.com/questions/51437/print-all-colorings-of-a-3x3-grid
### Python 3 - 93 bytes
```
for x in range(0,512):
    print("{:03b}\n{:03b}\n{:03b}\n".format(7&x,(56&x)>>3,(448&x)>>6))
```
## Print the f × f times table
https://codegolf.stackexchange.com/questions/103403/print-the-f-%c3%97-f-times-table/181950#181950
### Python 2 - 58 bytes
```
for i in range(256):r=i%16;print'%02x'%(i/16*r)+r/15*'\n',
```
## Is this number a repdigit?
https://codegolf.stackexchange.com/questions/125133/is-this-number-a-repdigit
### Python 2 - 28 bytes
```
b=raw_input();b[0]*len(b)==b
```
