<div align="center">

## A Simple Calculator


</div>

### Description

A simple Calculator ;

Well Commented easy to follow,

for beginers.

It also shows some basics of C++ programs. If you find this article helpful to you please send me a message.
 
### More Info
 
As the program will not make any error check, Dont enter any charactors other than numbers.


<span>             |<span>
---                |---
**Submitted On**   |
**By**             |[Saifudheen A A](https://github.com/Planet-Source-Code/PSCIndex/blob/master/ByAuthor/saifudheen-a-a.md)
**Level**          |Beginner
**User Rating**    |3.9 (27 globes from 7 users)
**Compatibility**  |C\+\+ \(general\), Microsoft Visual C\+\+, Borland C\+\+, UNIX C\+\+
**Category**       |[Math](https://github.com/Planet-Source-Code/PSCIndex/blob/master/ByCategory/math__3-12.md)
**World**          |[C / C\+\+](https://github.com/Planet-Source-Code/PSCIndex/blob/master/ByWorld/c-c.md)
**Archive File**   |[](https://github.com/Planet-Source-Code/saifudheen-a-a-a-simple-calculator__3-2819/archive/master.zip)





### Source Code

```
// This is a comment an will not make any sense to program
// Simple Calculator By A. A . Saifudheen
// keraleeyan@msn.com
// This Code is NOT copywrited and may distribute
// freely unless any comments are NOT Removed including above comments
#include <iostream.h> // This file used for function definitions 'cout' and 'cin' in program
//Simple Calculator By A. A . Saifudheen
float a; // floating point variable -Means a Variable that capable of storing a number having some decimal places
float b; //
float result;
int op; // Integer Variable -Means Variable that capable of storing a number. ( No decimal places)
int option;
int main()   // It is the main function. A function Named 'main' is required for all C++ programs
{
	do //'Do While' loop Used for Looping the program for multiple Calculations
	// 'Do While' loop Starts Here
	{
		cout << "Enter First Number \n";
		cin >> a; // Input
		cout << "Enter Second Number \n";
		cin >> b;
		cout << "Please enter an Option..\n";
		cout << "[1] Add \n";
		cout << "[2] Substract \n";
		cout << "[3] Multiply \n";
		cout << "[4] Devide \n ";
		// Add more function like Power, Modulus etc if needed.
		cin >> op; // The keybord input is passed to variable 'op'
		switch (op)  // switch is similar to Select Case in VB
		{
			case 1 : // Case Addition
				result=a+b;
				break;
			case 2 : //Case Substraction
				result=a-b;
				break;
			case 3 : // Case multiplication
				result=a*b;
				break;
			case 4 : // Case Division
				result=a/b;
		}
		cout <<"The Result is..= " << result << "\n\n"; //Display Result and Skipping two Lines
		cout << "Enter an Option..\n";
		cout << "[0] Exit.\n";
		cout << "[1] Continue. \n";
		cin >> option;
		// Do While loop Ends Here
	} while (option==1);	// If option is 1 ie 'Continue' the above code is Looped else ( option<>1 ) it is Escaped from Loop
	return 0;  // the ' main' function returns value 0
	}
// End of Code
```

