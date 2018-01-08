### introduction 
+ if elif
+ use tab rather than {}
+ range(5) : 0 1 2 3 4 
+ range(2,5) : 2 3 4 
+ use (and or) except (&& ||)
+ ":" for for loop  "in range" for the range of number 
```python
if __name__ == '__main__':
    n = int(raw_input())
    for i in range(n):
        print (i*i)
```
+ check : put if else statement into check 
```python
check = {True: "Not Weird", False: "Weird"}
print(check[
        n%2==0 and (
            n in range(2,6) or 
            n > 20)
    ])
```
+ print out without nextline
```python
print(x,end='') 
```
