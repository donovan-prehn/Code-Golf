# Code-Golf
https://codegolf.stackexchange.com/

## Palindrome
https://codegolf.stackexchange.com/questions/110582/im-a-palindrome-are-you

tl;dr - program classifies palindromes with program sourcecode itself being a palindrome.

```
S=input()#
print(S[::-1]==S)#)S==]1-::[S(tnirp
#)(tupni=S
```

## All colorings of a 3x3 grid
https://codegolf.stackexchange.com/questions/51437/print-all-colorings-of-a-3x3-grid
```
for x in range(0,512):
    print("{:03b}\n{:03b}\n{:03b}\n".format(7&x,(56&x)>>3,(448&x)>>6))
```

###Output
000
000
000
   
001
000
000
   
010
000
000

...

101
111
111
   
110
111
111
   
111
111
111
  
