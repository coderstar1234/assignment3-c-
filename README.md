<h1 align="center" >Even or Odd Checker</h1>

- This program checks whether a number entered by the user is even or odd using two different methods:<br> modulus operator and bitwise AND operator.
<hr>
<h1 align="center" >Prerequisites</h1>

- Before running the program, you need to have a C++ compiler installed on your machine.
- If you don't have one already, you can download and install GCC.

<h1 align="center" >How to Run the Program</h1>

- Open a command prompt or terminal window.
- Navigate to the directory where you have saved the program.
- Compile the program using the following command:

Copy code
g++ even_or_odd.cpp -o even_or_odd
- Replace even_or_odd.cpp with the name of the file containing the program code.

Run the program using the following command:
bash
Copy code
./even_or_odd
- Enter a number when prompted and press Enter.
- The program will then output whether the entered number is even or odd using both methods.

<h1 align="center" >How it Works</h1>

- The first program uses the modulus operator % to determine whether the entered number is even or odd. 
- If the remainder when the number is divided by 2 is zero, then the number is even, otherwise, it is odd.
- The second program uses bitwise AND operator & to check whether the least significant bit of the number is set to 1 or not.
- If it is 0, then the number is even, otherwise, it is odd.

<h1 align="center" >License</h1>

- This project is licensed under the MIT License - see the LICENSE file for details.
