# Looping-construct-in-pyhton

Hi!

- We use for loop when we want to run a block of code certain number of times.
 
- When we pass only one argument (considered as **`END_POINT`**) in the range function. The loop starts with **`0`** and runs till **`END_POINT - 1.`**
e.g:
for number in range(4):
    print(number)
    
    0 1 2 3

- When we pass two arguments (first one considered as START_POINT and second one as END_POINT). The loop start with START_POINT and runs till END_POINT -1.
e.g:
for number in range(1, 5):
    print(number)
    
    1 2 3 4

- When we pass three arguments (first one considered as START_POINT, second one as END_POINT and the last one is STEP).
e.g:
for number in range(1, 10, 2):
    print(number, end= ' ')
    
    1 3 5 7 9
    
    - Iterate a String using FOR LOOP
    e.g:
    for character in "analytics_vidhya":
    print(character)
    
a
n
a
l
y
t
i
c
s
_
v
i
d
h
y
a

- NESTED FOR LOOPS
A nested loop is a loop within a loop.
For each step in the outer loop, the inner loop exectues completely. See the below example

e.g:
# define the range of outer loop
for outer_loop_number in range(1, 3):
    
    # define the inner loop
    for inner_loop_character in "ABC":
        
        print(outer_loop_number, inner_loop_character)
        
 1 A
1 B
1 C
2 A
2 B
2 C

-WHILE LOOP
Another way to execute a block of code over and over again is using a while statement.
The code in a while clause will be executed as long as the while statement’s condition is True.

e.g:
In the below example, we have initialize the variable number = 0 and we will increment it's value in each iteration. The loop will only continue to run only if the value is less than 7.

number = 0

while (number < 7):
    print(number)
    number = number + 1
    
    0
1
2
3
4
5
6


Thank you!
