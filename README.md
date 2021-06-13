# CENG140 Section-1/2 THE2 Tester

Tester for the CENG 140 Section-1/2 Take Home Exam 2 in 2020-21 Spring Semester.

**Contributor**
- Reyhan Kalkan 
  
**Remarks:** 
- Tester is tested on Ubuntu. 
- Other linux distributions are not tested. Tester may work with other distributions.
- It will probably not work on Windows.


## Tester

Tester can be used to check outputs of your code and the pre-generated results.

### Prerequirements for Tester
- **GCC**:  
	Make sure that you have gcc in your system. GCC will be used to compile your code.  
  (The usage of gcc in tester (as an example): gcc functions.c ...)

### Usage
1. Extract cases.zip and results.zip in same directory.
	Prefer to use "Extract Here" option.
2. Copy your functions.c file to Tester directory.
	"functions.c" needs to be in same directory with "tester".
3. Open your terminal.
4. Make sure that you are on right directory.
5. Run "tester".

Tester will start checking your code. You should be able to see the progress on your terminal. After finishing testing, your results will be viewed on screen.  
If there is/are error(s), you should be able to see your errors in errors.txt. In errors.txt, you can see test case(s) and line(s) that error(s) occurred. You can see your output in "outputs" file.

### Reading Result/Output
There is not any indicator that shows you which lines belong to which functions. However, you can read the results/outputs by following way:
- In results, there is a block of float numbers. These are result of the function 1.
- After, there is a block of integer numbers. These are result of the function 2.
- After, there is a block of float numbers. These are result of the function 3.
- After, there is a single integer number. This is result of the function 4.
- After, there is a line of integer numbers. This is result of the function 5.
- After, there is a block of float numbers (50 lines). These are result of the function 6.
- After, there is a line of integer numbers. This is result of the function 7.
- After, there is a block of float numbers. These are result of the function 8.
- After, there is a line of integer numbers. This is result of the function 9.
- After, there is a line of integer numbers. This is result of the function 10.

## Disclaimer
The tester does not have to be error free. There is no guarantee of the accuracy of the inputs or results.