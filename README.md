# ProgrammingInterview

//Basic Function

Q1. Write a function that formats the bank account number (45106000760000404280042150 will convert to 45 1060 0076 0000 4042 8004 2150).

Q2. Transform the sentence so that the first character on each word is in upper case. However, you cannot use any of these functions:(ucfirst, ucwords, mb_convert_case)
    Sol. ebramha inc, professional software company.
    
Q3/OOPS. Create a new object $user1, and pass to the constructor the value of "first name" and "last name"
The first name is "John" and last name is "Doe". Get the full name, and echo it to screen.

Q4/OOPS. Create an object $admin1 out of the class Admin, set its name to "Bramha", and say hello to the user. Do you see any problem during executing?
What do you think is the cause of the problem?

	class User{
		
		private $username;

		public function setUsername($name){
			$this->username = $name;
		}		
		
	}
	
	class Admin extends User{
		public function sayHello(){
			return "Hello admin, ". $this->username;
		}
	}
    

//Intermediate

Q5/OOPS. Create an abstract class with the name of "User", which has an abstract method with the name of "stateYourRole" and property called "username". Create an Admin class that inherit "User" class, define "stateYourRole" method return string "Admin" & "Username" property return string "E-Bramha". Create an object from the "Admin" class and echo string "Admin E-Bramha".

Q6/OOPS. Create a class with the name of "User", Add a "setName" method a code that throws exception whenever the user's name is shorter than 3 letters. 
Feeds below array into the class, and handles the exception by echoing the custom messages.
$dataForUsers = array(array("Paul"), array("Bill"), array("li"), array("Kathy"), array("Sharon"));

Q7. Create a script to import the data from the file animals.csv to a database table
    1.Create a list of animals and page it records.
    2.Add functionality to add, edit and delete animals
    
Convert below table into animals.csv file

| id | threatened_animals |
| ------ | ----------- |
| 1   | Elephant |
| 2 | Tiger |
| 3    | Lion |
| 4    | Gorila |
| 5    | Gray Whale |
