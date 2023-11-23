
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


![Screenshot 2023-11-23 184016](https://github.com/noor307922/CPP/assets/125033135/5ea44f60-f0eb-4e8f-a15a-578bdac0db7f)
![Screenshot 2023-11-23 184113](https://github.com/noor307922/CPP/assets/125033135/4b8f9d53-84bf-435b-ac17-b3cdde95de06)
