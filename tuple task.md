# Basic Tuple Operations 
## INPUT
```
fruit=("apple","banana","cherry","apple","mango","banana")
print(fruit[0])
print(fruit[5])
x=(fruit)
print(x[0:3])
tuple1=("apple","banana","cherry","apple","mango","banana")
tuple2=("grape","kiwi")
tuple3=tuple1+tuple2
print(tuple3)
t1=("apple","banana","cherry","apple","mango","banana")
x=list(t1)
print(type(t1))
x.append("orange")
print(x)
student=("Alice",21,"Computer Science","delhi")
print(student[0])
print(student[3])
x=(student)
print("student age is 22" ,)
student=("Alice",22,"Computer Science","delhi")
print(student)
x=list(student)
print(type(student))
x.append("python")
print(x)
student=("Alice",22,"Computer Science","delhi")
(a,b,*t)=student
print(a)
print(b)
print(t)
x = (1, 2, 3, 4, 5)
x1 = ("A", "B", "C")
t=x,x1
for y in t:
    print(y)
    x = (1, 2, 3, 4, 5)
x1 = ("A", "B", "C")
t=x,x1
i=0
while i <len(t):
    print(t[i])
    i=i+1
    x = (1, 2, 3, 4, 5)
x1 = ("A", "B", "C")
x2=x+x1
print(x2)
x = (1, 2, 3, 4, 5)
x1 = ("A", "B", "C")
x2=x*2
print(x2)
x3=x1*3
print(x3)

```
#OUTPUT

```
apple
banana
('apple', 'banana', 'cherry')
('apple', 'banana', 'cherry', 'apple', 'mango', 'banana', 'grape', 'kiwi')
<class 'tuple'>
['apple', 'banana', 'cherry', 'apple', 'mango', 'banana', 'orange']
Alice
delhi
student age is 22
('Alice', 22, 'Computer Science', 'delhi')
<class 'tuple'>
['Alice', 22, 'Computer Science', 'delhi', 'python']
Alice
22
['Computer Science', 'delhi']
(1, 2, 3, 4, 5)
('A', 'B', 'C')
(1, 2, 3, 4, 5)
('A', 'B', 'C')
(1, 2, 3, 4, 5, 'A', 'B', 'C')
(1, 2, 3, 4, 5, 1, 2, 3, 4, 5)
('A', 'B', 'C', 'A', 'B', 'C', 'A', 'B', 'C')
