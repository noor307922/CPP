
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
