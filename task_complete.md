**1.What is list in Python .?**

* list is collective datatype in python which is ordered,indexed,heterogeneous collection of element separated by comma and allows duplicates.

ex:-

l=\[1,2,3,4]



**2. Why is a list called a mutable data type ?**

* because list is changeable. We can add , remove, and update element after creation. 



**3.What is the difference between append() and extend() ?**

* append is method of list , which is used to add element in list at last.
* ex: l=\[1,2,3,4,5]

&nbsp; l.append(6)

&nbsp;print(l)

-->\[1,2,3,4,5,6]



* Extend is also method of list which adds element in the list at last in iterable format.
* ex: l=\[1,2,3,4,5]

m=\[7,8,9,10]

l.extend(m)

print(l)

--> \[1,2,3,4,5,6,7,8,9,10]



4**.What is use of the insert() method ?**

* insert() method is used for inserting element at given index.

ex  l=\[1,2,3,4,5,6,7,8,9,10]

l.insert(2,33)

print(l)

-->\[1,2,33,3,4,5,6,7,8,9,10]





**5.What is difference between remove() and pop() ?**



**6.What is use of the index() method ?**

* return index of given element
* ex: l=\[1,2,3,4,5,6,7,8,9,10]

print(l.index(3))

--> 2





**7.What is the purpose of the count() method ?**

* count() method is used for to count element in the list
* ex: l=\[1,2,3,4,3,5]

l.count(3)

print(l)

-->2





**8.What is the difference between sort() and Sorted() ?**

* sort() method assign element at accending order.
* ex: l=\[7,6,5,1,2,3]

l.sort()

print(l)

-->\[1,2,3,4,5,6,7]



**9.What is the use of the reverse() method ?**

* Used to reverse the sequence of element.
* ex:

l=\[1,2,3,4,5]

l.reverse()

print(l)

--> \[5,4,3,2,1]





**10.What happens when we use the Clear() method on a list ?**

* when we use clear() method all elements in the list are removed .
* ex.   

&nbsp;l=\[1,2,3,4,5]

l.clear()

print(l)

-->\[]

