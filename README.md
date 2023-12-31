
### ***Title*** : LAB5
### ***Aim*** : Recursion
(1) Addition of first n integers

(2) Factorial of n

(3) Print reverse of string

(4) Print reverse of number

### ***Algorithm*** :
(1) First create function declarations and definitions

(2) Write the logic for the functions using recursion

(3) Call the functions

### ***Explanation*** :
(1) sum(n) = n+sum(n-1)

(2) fact(n) = n*fact(n-1)

(3) str="welcome" -> w+rev_the_string(elcome) and so on and we get emoclew

(4) number=45 -> 6+rev_the_number(54) and so on and we get 54

Output :![Screenshot 2023-11-23 171050](https://github.com/noor307922/CPP/assets/125033135/efd21e47-05fb-4952-93f5-8abf0171ab9b)


### ***Title*** : LAB6 'A'
### ***Aim***: To print five digit number in words.
### ***Algorithm*** : 
(1) Create ptr to array of digit_str from one to nine,Create ptr to array of two_digit_str from ten to nineteen,Create ptr to array of tens_str from twenty to ninety

(2) Get the five digit number from user

(3) Check for the condition if the number is greater than 9999 and less than 100000

(4) Print the units tens hundreds thousands ten thousand

### ***Output***
![Screenshot 2023-11-23 175712](https://github.com/noor307922/CPP/assets/125033135/98c7b663-e73a-40c3-9e1a-276ae17e21a0)


### ***Title*** : LAB6 'B'
### ***Aim*** : 
(1) Write a program to declare a char array of 20 characters. Read a word(using scanf or cin>>) into the char array.

(2) Display the array and reverse of the array on screen.

(3) Check if the word is a palindrome(A word is a palindrome if it reads same either straight or reverse e.g. "madam")

(4) Using pointer please calculate length of the word.

### ***Algorithm*** :
First declare a char array with size 20.

Use cin(>>) to read a word

Using for loop iterate and print the array and store it in a arr

Using for loop iterate and print the reverse of the array and store it in reverse_arr

Check the word is palindrome or not using if statement

Using ptr print the length of the word.

### ***Output*** :
![Screenshot 2023-11-23 180804](https://github.com/noor307922/CPP/assets/125033135/962febf6-deae-4f4b-a1c1-b05d412fbf19)

![Screenshot 2023-11-23 181435](https://github.com/noor307922/CPP/assets/125033135/46738a6c-d01b-489f-88ea-52ac045953fb)


### ***Title*** : LAB7
### ***Aim*** : 
Reading from an xcel(.csv) file Name and Age using r(read) mode and storing as structure using malloc dynamic memory allocation

Writing to a file Name and Age using a(append) mode

### ***Algorithm*** :

Reading from a CSV File and Storing as a Structure

***Algorithm for part1***:

Open the CSV file for reading.

Check if the file was opened successfully. If not, display an error message and exit.

Create a structure (in this case, Person) to store the data from each line of the CSV file. The structure contains two members: a character pointer for the name and an integer for the age.

Create a vector or another suitable data structure to hold instances of the Person structure.

Read each line from the CSV file using std::getline.

Tokenize the line by splitting it at each comma (,). For this, you can use strtok.

Extract the name and age from the tokens and store them in a new instance of the Person structure.

Add the Person structure to your data structure (e.g., a vector) if the tokenization is successful.

Print the data from the data structure (e.g., the vector).

Free the dynamically allocated memory to prevent memory leaks.

Writing to a File in Append Mode

***Algorithm for part2***:

Open the file in append mode using ofstream with the ios::app flag.

Check if the file was opened successfully. If not, display an error message and exit.

Create a structure (in this case, Person) to store the data to be written to the file. The structure contains a string for the name and an integer for the age.

Input the name and age from the user.

Write the name and age to the end of the file using the << operator.

Close the file.


Output:
Part 1

![Screenshot 2023-11-23 184016](https://github.com/noor307922/CPP/assets/125033135/5ea44f60-f0eb-4e8f-a15a-578bdac0db7f)
![Screenshot 2023-11-23 184113](https://github.com/noor307922/CPP/assets/125033135/4b8f9d53-84bf-435b-ac17-b3cdde95de06)


### ***Title*** : LAB8 & LAB9
### ***Aim*** : Write a class (date), access its functions using class object (today)
### ***Algorithm*** : 
(1) Create a class named date

(2) Initialize int arr month_days, initialize ptr to strings months and weekdays

(3) Take day, month, year from user

(4) Display the date in slashed form with the help of disp_date() function

(5) Check whether the year entered by user is leap or not leap by using is_leap()

Output : 
(6) Calculate the total days from Jan 1 to current date day_of_year()

(7) Display the date without slashed form using disp_date1()

(8) Display the weekday for the current date using disp_weekday()

Output :
![Screenshot 2023-11-23 194756](https://github.com/noor307922/CPP/assets/125033135/8f6b129b-35c9-44e1-9241-9d4678905448)



### ***Title*** : LAB10
### ***Aim*** : Operator Overloading
### ***Algorithm*** :

Initialize Date Class:

Create a class called Date with private variables for day, month, and year.
Implement a constructor to set the initial date, and a display function to print the date.

Leap Year Check:
Create a function (isLeapYear) to check if a given year is a leap year.
A leap year is divisible by 4, but century years must also be divisible by 400.

Days in Month:
Create a function (daysInMonth) to determine the number of days in the current month.
February has 29 days in a leap year and 28 days otherwise.
April, June, September, and November have 30 days, while other months have 31 days.

Overloaded ++ Operator:
Overload the ++ operator as a member function in the Date class.
Increment the day by 1.
Check if the new day exceeds the number of days in the month.
If yes, reset the day to 1 and increment the month.
If the month exceeds 12, reset the month to 1 and increment the year.

Main Function:
In the main function, create an instance of the Date class with an initial date.
Display the current date.
Use the overloaded ++ operator to increment the date by one day.
Display the updated date.

Output :
![Screenshot 2023-11-23 195425](https://github.com/noor307922/CPP/assets/125033135/a4ef82f5-7445-4b6e-afbd-f13f3c407599)



### ***Title*** : LAB11
### ***Aim*** : Inheritance
### ***Algorithm*** : 

Algorithm for Constructor Calling in Inheritance:

The base class constructor is called first.

The derived class constructor is called after the base class constructor.

The constructors are called in the order of inheritance, meaning the base class constructor is called before the derived class constructor.

### ***Explanation*** :

Base Class Constructor Call:

When a derived class object is created, the constructor of the base class is called first. This is because the derived class inherits the properties and behavior of the base class, and before any additional initialization specific to the derived class, the base class needs to be properly constructed. If the base class has a parameterized constructor, the derived class's constructor must call it explicitly, passing the required arguments.

Derived Class Constructor Call:

After the base class constructor has been executed, the derived class constructor is called. The derived class constructor can perform its own initialization and may also call the base class constructor explicitly using the base class's constructor within its member initializer list.

Order of Inheritance:

The order in which constructors are called is determined by the order of inheritance. In the example above, Derived publicly inherits from Base, so the Base class constructor is called before the Derived class constructor. If there were multiple base classes, they would be initialized in the order they are listed in the inheritance declaration.

In summary, when a derived class object is defined in C++, the constructors are called in a well-defined order: first the base class constructor(s), in the order of inheritance, and then the derived class constructor. You can use member initializer lists to explicitly call base class constructors if needed. This ensures proper initialization and allows you to set up the derived class's specific behavior while inheriting the characteristics of the base class.


Output :
![Screenshot 2023-11-23 195851](https://github.com/noor307922/CPP/assets/125033135/8d03783c-5147-49f0-9b8e-d21977857b93)


### ***Title*** : LAB12
### ***Aim*** : Linked List
### ***Algorithm*** : 
Imagine a linked list as a chain of containers, where each container holds something special. In our case, each container is a "node" that stores a number, and it has a pointer pointing to the next container in the chain.

Starting Point:

We have a special pointer called "head" that tells us where our chain of containers begins. At the beginning, it points to nothing (nullptr) because our chain is empty.

Adding a Number at the Beginning:
Imagine we have a new container.
We put our desired number in this new container.
We make the new container point to where the head is pointing.
We update the head to point to our new container.

Adding a Number at the End:
Imagine we have a new container.
We put our desired number in this new container.
If our chain is empty, we make the head point to our new container.
If our chain is not empty, we find the last container and make it point to our new container.

Removing a Number from the Beginning:
If our chain is empty, we say, "Sorry, there's nothing to remove."
If our chain is not empty, we look at the first container and remember it.
We update the head to point to the next container.
We say goodbye to the container we remembered.

Removing a Number from the End:
If our chain is empty, we say, "Sorry, there's nothing to remove."
If there's only one container, we remove it and update the head to nullptr.
If there's more than one container, we find the second-to-last container.
We make the second-to-last container point to nullptr, and we remove the last container.

Displaying the Numbers:
We start at the head and look inside each container.
We shout out the number we find.
We move to the next container and repeat until we reach the end, where we shout "NULL."

Main Function and Menu:
We show a menu with choices like "Add at the Beginning," "Add at the End," "Remove from the Beginning," "Remove from the End," "Display," and "Exit."
We ask the user to pick a choice.
Based on the choice, we perform the corresponding action (adding, removing, displaying).
We keep doing this until the user says, "I'm done" (chooses "Exit").

In a nutshell, our linked list is like a chain of containers, and we can add, remove, and see the numbers inside those containers based on what the user wants.


Output : 

![Screenshot 2023-11-23 200745](https://github.com/noor307922/CPP/assets/125033135/259d2143-699f-4362-99b6-90b54bb4ca14)


### ***Title*** : LAB13
### ***Aim*** : Stack Implementation
### ***Algorithm*** :

Stack Operations:

Push:
Add an element to the top of the stack.
If the stack is full, display an error message (stack overflow).

Pop:
Remove the element from the top of the stack.
If the stack is empty, display an error message (stack underflow).

Display:
Show all elements in the stack from the bottom to the top.
If the stack is empty, indicate that it's empty.

Peek:
View the element at the top of the stack without removing it.
If the stack is empty, indicate that it's empty.

Exit:
End the program.

Stack Implementation:
The stack is implemented using an array and a variable (top) that keeps track of the top element's position.
isFull checks if the stack is full, and isEmpty checks if it's empty.
push adds an element to the top of the stack if it's not full.
pop removes the top element if the stack is not empty.
display shows all elements if the stack is not empty.
peek shows the top element without removing it if the stack is not empty.

Menu:
The program displays a menu with options for push, pop, display, peek, and exit.
It prompts the user to enter their choice and performs the corresponding operation.
If an invalid choice is entered, it displays an error message.

Main Loop:
The program continues to execute until the user chooses to exit.
It repeats the menu and operation execution based on the user's input.

Output :

![Screenshot 2023-11-23 202429](https://github.com/noor307922/CPP/assets/125033135/86ac0e77-e1f6-4c65-88c8-29ef6def71fe)

![Screenshot 2023-11-23 202455](https://github.com/noor307922/CPP/assets/125033135/17af82cf-dd79-4520-8a08-ab8598806911)

### ***Title*** : LAB14-Queue
### ***Aim*** : Queue Implementation
### ***Algorithm*** : 

Enqueue (Add an element to the queue):
If the queue is not full, we can add an element to it.
If the queue is empty, set both the front and rear pointers to the first position.
Otherwise, move the rear pointer to the next position and store the new element there.

Dequeue (Remove an element from the queue):
If the queue is not empty, we can remove an element from it.
If the queue has only one element, set both the front and rear pointers to -1 (indicating an empty queue).
Otherwise, move the front pointer to the next position.

Display (Show all elements in the queue):
If the queue is not empty, we can display its elements.
Start from the front and move towards the rear, showing each element one by one.

Peek (Get the front element without removing it):
If the queue is not empty, we can see the element at the front without removing it.
Simply display the element at the front position.

Output :-![Screenshot 2023-11-28 233944](https://github.com/noor307922/CPP/assets/125033135/82717bdb-38d7-406b-9f48-9ee9ecc23b24)



![Screenshot 2023-11-28 234028](https://github.com/noor307922/CPP/assets/125033135/9a5dd2c7-679e-43e0-a834-8ce93d5395ad)


### ***Title*** : LAB15
### ***Aim*** :

(1) Linear search

(2) Binary search

### ***Algorithm*** :

Linear Search Algorithm:

Input: An array arr of size n and a target element target.

Output: The index of the target element in the array if found, or -1 if not found.

Start at the first element of the array (index 0).

Repeat the following steps for each element in the array, starting from index 0 and moving to the end of the array.

a. Check if the current element is equal to the target element.

b. If the current element is equal to the target, return the index of the current element.

If the loop completes without finding the target, return -1 to indicate that the target element is not in the array.

Binary Search Algorithm:

Input: A sorted array arr of size n and a target element target.

Output: The index of the target element in the array if found, or -1 if not found.

Initialize two pointers, left and right, to the first and last indices of the array, respectively.

While left is less than or equal to right, do the following:

a. Calculate the middle index mid as (left + right) / 2.

b. If the element at mid is equal to the target, return mid.

c. If the element at mid is less than the target, update left to mid + 1 to search the right half.

d. If the element at mid is greater than the target, update right to mid - 1 to search the left half.

If the loop completes without finding the target, return -1 to indicate that the target element is not in the array.

These algorithms provide two different methods for searching for an element in an array. Linear search is straightforward but less efficient, especially for large arrays. Binary search, on the other hand, is highly efficient for sorted arrays, as it reduces the search space by half at each step, making it much faster for large datasets.

Output :

![Screenshot 2023-11-23 203309](https://github.com/noor307922/CPP/assets/125033135/6d51416e-44ed-4145-8ec7-906c9946e7ea)


![Screenshot 2023-11-23 203452](https://github.com/noor307922/CPP/assets/125033135/a04f8545-9c63-4386-a49a-f6d033beb3e8)



### ***Title*** : LAB16
### ***Aim*** : Trees
### ***Algorithm*** :

1. Node Insertion Algorithm:

Objective: Add a new number to the tree while maintaining the order.

Steps:

If the tree is empty, create a new node with the given number and make it the root.
If the number is smaller than the current node's number, go to the left subtree and repeat step 1.
If the number is larger, go to the right subtree and repeat step 1.
Return the modified tree.

2. Tree Traversal Algorithms:

a. Inorder Traversal:

Objective: Visit all nodes in ascending order.

Steps:

Go to the left subtree and repeat the process.
Visit the current node.
Go to the right subtree and repeat the process.

b. Preorder Traversal:

Objective: Visit the current node before its children.

Steps:

Visit the current node.
Go to the left subtree and repeat the process.
Go to the right subtree and repeat the process.

c. Postorder Traversal:

Objective: Visit the current node after its children.

Steps:

Go to the left subtree and repeat the process.
Go to the right subtree and repeat the process.
Visit the current node.

3. Node Deletion Algorithm:

Objective: Remove a number from the tree.

Steps:

If the tree is empty, do nothing.
If the number is smaller than the current node's number, go to the left subtree and repeat the process.
If the number is larger, go to the right subtree and repeat the process.

If the number is found:

a. If the node has no children (leaf node), delete it.
b. If the node has one child, replace it with its child.
c. If the node has two children, find the smallest node in the right subtree, replace the current node's data with it, and repeat the process for the right subtree.

4. Menu-Driven Interface:

Objective: Provide a user-friendly way to interact with the tree operations.

Steps:

Display a menu with options to insert, traverse, delete, or exit.
Based on the user's choice:
Insert a number into the tree.
Display the tree using different traversal methods.
Delete a node from the tree.
Exit the program.

This menu-driven interface allows users to perform various operations on the Binary Search Tree interactively.

Output:

![Screenshot 2023-11-23 204025](https://github.com/noor307922/CPP/assets/125033135/721845ef-1c14-420d-a395-5939deb2010c)


![Screenshot 2023-11-23 204107](https://github.com/noor307922/CPP/assets/125033135/f6282536-dd72-49cb-a22a-e127de49fa49)


![Screenshot 2023-11-23 204122](https://github.com/noor307922/CPP/assets/125033135/fa06bb60-2631-42f7-8910-f989b2c40391)



### ***Title*** : LAB17-Sorting
### ***Aim*** : Sorting Algorithms (Selection sort, Insertion sort, Bubble sort)
### ***Algorithm*** :

Selection Sort:
Start: Begin with the first element of the array.
Find Minimum: Find the smallest element in the unsorted part of the array.
Swap: Swap the found minimum element with the first element of the unsorted part.
Repeat: Repeat the above steps for the remaining unsorted part of the array.
End: The array is sorted when all elements are considered.

Insertion Sort:
Start: Begin with the second element of the array.
Insert: Insert this element into its correct position among the already sorted elements to its left.
Shift: If needed, shift the larger sorted elements to make space for the inserted element.
Repeat: Repeat the above steps for the remaining unsorted part of the array.
End: The array is sorted when all elements are considered.

Bubble Sort:
Start: Begin with the first element of the array.
Compare: Compare the current element with the next element.
Swap: If the current element is greater than the next element, swap them.
Repeat: Repeat steps 2 and 3 for all elements in the array.
One Pass: After one pass, the largest unsorted element is at the end of the array.
Repeat: Repeat steps 2-5 for the remaining unsorted part of the array.
End: The array is sorted when no more swaps are needed.

Output :-

![Screenshot 2023-11-28 235044](https://github.com/noor307922/CPP/assets/125033135/7b1e311e-4228-48df-b364-9f0c3eb2365d)

### ***Title*** : LAB18-Graph
### ***Aim*** : Graph Data Structure
### ***Algorithm*** :

Adjacency Matrix to Adjacency List:

Initialize an empty adjacency list for each vertex.

For each row in the adjacency matrix:
Create an empty list to represent the neighbors of the current vertex.

For each entry in the row:

If the entry is non-zero (indicating an edge):

Add the corresponding column index to the list of neighbors for that vertex.

Repeat steps 2-3 for each row in the matrix.

The resulting lists represent the adjacency list for each vertex.

Adjacency List to Adjacency Matrix:

Initialize an empty adjacency matrix with all entries set to zero.

For each vertex in the adjacency list:

For each neighbor in the list:

Set the corresponding entry in the adjacency matrix to 1.

Repeat step 2 for each vertex in the adjacency list.

The resulting matrix represents the adjacency matrix for the graph.

### ***Output*** 

![Screenshot 2023-11-29 000138](https://github.com/noor307922/CPP/assets/125033135/3f56f69a-bef7-4159-a81e-e4591c7f2427)
