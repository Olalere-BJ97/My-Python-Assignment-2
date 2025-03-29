# My-Python-Assignment-2
Question.
Create an empty list called my_list.
Append the following elements to my_list: 10, 20, 30, 40.
Insert the value 15 at the second position in the list.
Extend my_list with another list: [50, 60, 70].
Remove the last element from my_list.
Sort my_list in ascending order.
Find and print the index of the value 30 in my_list.

Answer 
Creating and Modifying the List
``
Create an empty list called my_list
my_list = []

Append elements to my_list
my_list.append(10)
my_list.append(20)
my_list.append(30)
my_list.append(40)

Insert the value 15 at the second position in the list
my_list.insert(1, 15)

Extend my_list with another list
my_list.extend([50, 60, 70])

Remove the last element from my_list
my_list.pop()

Sort my_list in ascending order
my_list.sort()

Print the list
print(my_list)

Find and print the index of the value 30 in my_list
print(my_list.index(30))
```

Output:
```
[10, 15, 20, 30, 40, 50, 60]
3
```

In this code:

1. We first create an empty list called `my_list`.
2. We append the elements 10, 20, 30, and 40 to `my_list` using the `append` method.
3. We insert the value 15 at the second position in the list using the `insert` method.
4. We extend `my_list` with another list containing the elements 50, 60, and 70 using the `extend` method.
5. We remove the last element from `my_list` using the `pop` method.
6. We sort `my_list` in ascending order using the `sort` method.
7. Finally, we find and print the index of the value 30 in `my_list` using the `index` method.
