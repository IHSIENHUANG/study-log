#Basic Data Type
## List: 
+ List = []
1. insert i e: Insert integer  at position .
2. print: Print the list.
3. remove e: Delete the first occurrence of integer .
4. append e: Insert integer  at the end of the list.
5. sort: Sort the list.
6. pop: Pop the last element from the list.
7. reverse: Reverse the list.
+ eval format:
https://www.hackerrank.com/challenges/python-lists/problem

```python
if __name__ == '__main__':
    N = int(raw_input())
    LIST = []
    for _ in range (N):
        input_list = raw_input().split(' ');
        cmd = input_list[0];
        if(cmd == "insert"):
            eval("LIST.{0}({1},{2})".format(cmd,input_list[1],input_list[2]))
        elif (cmd == "append" or cmd =="remove"):
            eval("LIST.{0}({1})".format(cmd,input_list[1]))
        elif (cmd =="print"):
            print LIST
        else:
            eval("LIST.{0}()".format(cmd))
```
## tuple hash
