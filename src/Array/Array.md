---
layout: default
title: Array
nav_order: 14
---
### C++ Array
-----

An array in C++ is a collection of items stored at contiguous memory locations and elements can be accessed randomly using indices of an array. They are used to store similar type of elements as in the data type must be the same for all elements. They can be used to store collection of primitive data types such as int, float, double, char, etc of any particular type. To add to it, an array in C or C++ can store derived data types such as the structures, pointers etc. 


####Why do we need arrays? 
-----

We can use normal variables (v1, v2, v3, ..) when we have a small number of objects, but if we want to store a large number of instances, it becomes difficult to manage them with normal variables. The idea of an array is to represent many instances in one variable.

```objectivec
// Array declaration by specifying size

int arr1[10];
 
// With recent C/C++ versions, we can also
// declare an array of user specified size
int n = 10;
int arr2[n];
```

```objectivec
// Array declaration by initializing elements

int arr[] = { 10, 20, 30, 40 }
 
// Compiler creates an array of size 4.
// above is same as  "int arr[4] = {10, 20, 30, 40}"
```

```objectivec
// Array declaration by specifying size and initializing elements

int arr[6] = { 10, 20, 30, 40 }
 
// Compiler creates an array of size 6, initializes first
// 4 elements as specified by user and rest two elements as
// 0. above is same as  "int arr[] = {10, 20, 30, 40, 0, 0}"
```

####Advantages of an Array in C/C++: 
-----

1.Random access of elements using array index.
2.Use of less line of code as it creates a single array of multiple elements.
3.Easy access to all the elements.
4.Traversal through the array becomes easy using a single loop.
5.Sorting becomes easy as it can be accomplished by writing less line of code.

####Disadvantages of an Array in C/C++: 
-----

1.Allows a fixed number of elements to be entered which is decided at the time of declaration. Unlike a linked list, an array in C is not dynamic.
2.Insertion and deletion of elements can be costly since the elements are needed to be managed in accordance with the new memory allocation.