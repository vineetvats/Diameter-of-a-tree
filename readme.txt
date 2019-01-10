Team Members: Punit Bhalla and Vineet Vats

Steps to compile and run the code:

There are basically two ways by which you can run this code:
1. Using Command Line
2. Using IDE

Note: First of all extract the folder pxb173830 from zip file "pxb173830.zip". Make sure BFSOO.java and Graph.java is present inside rbk package.

1. Steps to run the code using Command Line:
 Step1: Copy the package folder  i.e. pxb173830 to any location on your PC.
 Step2: Open terminal or command line interface and go to the parent folder of the package folder using cd command.
 Step3: Compile files using following command:
 		$ javac pxb173830/SP12.java
 Step4: Run the code using following command:
	    	$ java pxb173830/SP12
	    
2. Steps to run the code using IDE:
 Step1: Create a simple java project. For example if you are using eclipse then go to File->New->Project->Java Project.
 Step2: Copy the package folder pxb173830 under src folder.
 Step3: Right click on the project name and build the project.
 Step4: Right click on the project name, go to "Run as" option and then click on "Java Application".
 Step5: Select SP12 from the available files to execute the code.



I/O specifications
	    
Sample Input: 
String string = "10 9   1 2 2   1 3 3   2 4 5   2 5 4   3 6 1   3 7 1   4 8 1   7 9 1   7 10 1"; //Source vertex is 10 (vertex with highest number)

Output:

Graph: n: 10, m: 9, directed: false, Edge weights: false
1 :  (1,2) (1,3)
2 :  (1,2) (2,4) (2,5)
3 :  (1,3) (3,6) (3,7)
4 :  (2,4) (4,8)
5 :  (2,5)
6 :  (3,6)
7 :  (3,7) (7,9) (7,10)
8 :  (4,8)
9 :  (7,9)
10 :  (7,10)
______________________________________________

Diameter of tree: 6
