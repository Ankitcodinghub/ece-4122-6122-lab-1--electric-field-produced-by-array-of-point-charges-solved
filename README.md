# ece-4122-6122-lab-1--electric-field-produced-by-array-of-point-charges-solved
**TO GET THIS SOLUTION VISIT:** [ECE 4122/6122 Lab 1- Electric Field Produced by Array of Point Charges Solved](https://www.ankitcodinghub.com/product/ece-4122-6122-lab-1-electric-field-produced-by-array-of-point-charges-solved/)


---

📩 **If you need this solution or have special requests:** **Email:** ankitcoding@gmail.com  
📱 **WhatsApp:** +1 419 877 7882  
📄 **Get a quote instantly using this form:** [Ask Homework Questions](https://www.ankitcodinghub.com/services/ask-homework-questions/)

*We deliver fast, professional, and affordable academic help.*

---

<h2>Description</h2>



<div class="kk-star-ratings kksr-auto kksr-align-center kksr-valign-top" data-payload="{&quot;align&quot;:&quot;center&quot;,&quot;id&quot;:&quot;127125&quot;,&quot;slug&quot;:&quot;default&quot;,&quot;valign&quot;:&quot;top&quot;,&quot;ignore&quot;:&quot;&quot;,&quot;reference&quot;:&quot;auto&quot;,&quot;class&quot;:&quot;&quot;,&quot;count&quot;:&quot;2&quot;,&quot;legendonly&quot;:&quot;&quot;,&quot;readonly&quot;:&quot;&quot;,&quot;score&quot;:&quot;5&quot;,&quot;starsonly&quot;:&quot;&quot;,&quot;best&quot;:&quot;5&quot;,&quot;gap&quot;:&quot;4&quot;,&quot;greet&quot;:&quot;Rate this product&quot;,&quot;legend&quot;:&quot;5\/5 - (2 votes)&quot;,&quot;size&quot;:&quot;24&quot;,&quot;title&quot;:&quot;ECE 4122\/6122 Lab 1- Electric Field Produced by Array of Point Charges Solved&quot;,&quot;width&quot;:&quot;138&quot;,&quot;_legend&quot;:&quot;{score}\/{best} - ({count} {votes})&quot;,&quot;font_factor&quot;:&quot;1.25&quot;}">

<div class="kksr-stars">

<div class="kksr-stars-inactive">
            <div class="kksr-star" data-star="1" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="2" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="3" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="4" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="5" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
    </div>

<div class="kksr-stars-active" style="width: 138px;">
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
    </div>
</div>


<div class="kksr-legend" style="font-size: 19.2px;">
            5/5 - (2 votes)    </div>
    </div>
(100 pts)

Objective:

To understand and apply the principles of class creation and inheritance in C++ while leveraging std::thread for parallel calculations in a computationally-intensive problem related to the Electric Field calculations.

Description:

You will use the formula below to calculate the electric field vector:

𝐸𝐸⃗ = 𝑟𝑟2 𝑟𝑟̂

where,

𝐸𝐸⃗ is the electric field vector,

𝑞𝑞 is magnitude of the charge of the point,

𝑘𝑘 is Coulomb’s constant = 9×109 Nm2/C2,

𝑟𝑟 is the radial distance between the point charge and the (x, y, z) location in space, 𝑟𝑟̂ is the unit vector from the point charge to the (x, y, z) location in space.

Your code should include the following:

Base Class: ECE_PointCharge in files ECE_PointCharge.h &amp; ECE_PointCharge.cpp

Protected members variables:

• double x; // x-coordinate.

• double y; // y-coordinate.

• double z; // z-coordinate.

• double q; // charge of the point.

Public member functions:

• A constructor that initializes the above member variables.

• A function void setLocation (double x, double y, double z);

• A function void setCharge (double q);

Derived Class: ECE_ElectricField in files ECE_ElectricField.h &amp; ECE_ElectricField.cpp

Inherits from: ECE_PointCharge

Protected additional member variables:

• double Ex; // Electric field in the x-direction.

• double Ey; // Electric field in the y-direction.

• double Ez; // Electric field in the z-direction.

Public member functions:

• A constructor that initializes base class member variables.

• void getElectricField(double &amp;Ex, double &amp;Ey, double Ez);

OverView:

Create an application that uses the above classes and multithreading to calculate the electric field at a point in space.

• Your program should notify the user how many threads can run concurrently when doing the calculation.

• Your program needs to query the user for the size of the N x M array and the charge q.

• Your program should continuously prompt the user if a new calculation is wanted.

• Your program should use multithreading to reduce the processing time taken.

• After calculating the resultant electric field your program should output the Ex, Ey, Ez values and the resultant electric field strength.

• Your program should also output how long it takes in microseconds from the time the user inputs the xyz location to just before the results are output to the screen.

• Spaces separate the values when entering multiple inputs.

• Make sure you check for valid inputs o N and M should be natural numbers.

o Separation distances should be &gt; 0.0 and be valid numerical values o Charge should be a valid numerical value.

o Point location should be made up of valid numerical values.

• Use multithreading to breakup the array so that each thread does the calculations for part of the array.

Sample Program Flow:

 Your computer supports ## concurrent threads.

 Please enter the number of rows and columns in the N x M array: 100 100

 Please enter the x and y separation distances in meters: 0.01 0.03

 Please enter the common charge on the points in micro C: 0.02



 Please enter the location in space to determine the electric field (x y z) in meters: 1.0 2.0 3.0  The electric field at (1.0, 2.0, 3.0) in V/m is  Ex = x.xxxx * 10^y

 Ey = x.xxxx * 10^y

 Ez = x.xxxx * 10^y

 |E| = x.xxxx * 10^y

 The calculation took x.xxxx microsec!

 Do you want to enter a new location (Y/N)? Y



 Please enter the location in space to determine the electric field (x y z) in meters: 2.0 2.0 2.0  The electric field at (2.0, 2.0, 2.0) in V/m is  Ex = x.xxxx * 10^y

 Ey = x.xxxx * 10^y

 Ez = x.xxxx * 10^y

 |E| = x.xxxx * 10^y

 The calculation took x.xxxx microsec!  Do you want to enter a new location (Y/N)? N  Bye!



Turn-In Instructions

Place your files in a zip file called Lab1.zip and upload this zip file on the assignment section of Canvas.

Grading Rubric:

AUTOMATIC GRADING POINT DEDUCTIONS PER PROBLEM:

Element Percentage Deduction Details

Does Not Compile 40% Code does not compile on PACE-ICE!

Does Not Match Output Up to 90% The code compiles but does not produce correct outputs.

Runtime and efficiency of code setup Up to 20% The code generates the correct output but runs slower than expected.

Clear Self-Documenting Coding Styles Up to 25% This can include incorrect indentation, using unclear variable names, unclear/missing comments, or compiling with warnings. (See Appendix A)

LATE POLICY

Element Percentage Deduction Details

Appendix A: Coding Standards

Indentation:

When using if/for/while statements, make sure you indent 4 spaces for the content inside those. Also make sure that you use spaces to make the code more readable. For example:

for (int i; i &lt; 10; i++)

{ j = j + i;

}

If you have nested statements, you should use multiple indentions. Each { should be on its own line (like the for loop) If you have else or else if statements after your if statement, they should be on their own line.

for (int i; i &lt; 10; i++)

{

if (i &lt; 5) { counter++; k -= i; } else

{ k +=1; } j += i;

}

Camel Case:

This naming convention has the first letter of the variable be lower case, and the first letter in each new word be capitalized (e.g. firstSecondThird).

This applies for functions and member functions as well!

The main exception to this is class names, where the first letter should also be capitalized.

Variable and Function Names:

Your variable and function names should be clear about what that variable or function represents. Do not use one letter variables, but use abbreviations when it is appropriate (for example: “imag” instead of

“imaginary”). The more descriptive your variable and function names are, the more readable your code will be. This is the idea behind self-documenting code.

File Headers:

Every file should have the following header at the top

/*

Author: your name

Class: ECE4122 or ECE6122 (section)

Description:

What is the purpose of this file?

*/

Code Comments:

1. Every function must have a comment section describing the purpose of the function, the input and output parameters, the return value (if any).

2. Every class must have a comment section to describe the purpose of the class.

3. Comments need to be placed inside of functions/loops to assist in the understanding of the flow of the code.
