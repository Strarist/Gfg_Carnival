# Easy
# Question_1:-
Predict the output of the given program:
``` python
a="Bennett University"
for i in range(0,len(a),2):
    if(a[i]in 'aeiouAeiou'):
        print(ord(a[i]))
    else:
        print(a[i])
```
# Output:
B
n
101
t
U
105
101
s
t

# Question_2:-
Predict the pattern that is being printed in the given program:
``` python
x=5
for i in range(x):
    print((x-i)*' '+(i+1)*'*')
```
# Output:

     *
    **
   ***
  ****
 *****

# Question_3:
Predict the output of the given program by thouroughly going through the fucntions being performed of the given list:
``` python
a=[4,5,2,12,4,2,7,10,12,2,10]
a.reverse()
a.sort()
a.reverse()
a.append(8)
x=[]
for i in a:
    if i not in x:
        x.append(i)
print(x)
```
# Output:
[12, 10, 7, 5, 4, 2, 8]

# Question_4:
Predict the output of the given program by thouroughly going through the fucntions being performed of the given list:
``` python
a=[1,4,3,5,2,4,2,4,5,6,7,6]
b=[];c=[]
for i in a:
    for j in a:
        if(i==j):
            b.append(j)
            a.remove(j)
    c.append(b)
    b=[]
print(c)
```
# Output:
[[1], [3], [2, 2], [4, 4], [7]]
