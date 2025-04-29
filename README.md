# program-design-project-3-solved
**TO GET THIS SOLUTION VISIT:** [Program Design Project 3 Solved](https://www.ankitcodinghub.com/product/project-3-program-design-solved/)


---

📩 **If you need this solution or have special requests:** **Email:** ankitcoding@gmail.com  
📱 **WhatsApp:** +1 419 877 7882  
📄 **Get a quote instantly using this form:** [Ask Homework Questions](https://www.ankitcodinghub.com/services/ask-homework-questions/)

*We deliver fast, professional, and affordable academic help.*

---

<h2>Description</h2>



<div class="kk-star-ratings kksr-auto kksr-align-center kksr-valign-top" data-payload="{&quot;align&quot;:&quot;center&quot;,&quot;id&quot;:&quot;110283&quot;,&quot;slug&quot;:&quot;default&quot;,&quot;valign&quot;:&quot;top&quot;,&quot;ignore&quot;:&quot;&quot;,&quot;reference&quot;:&quot;auto&quot;,&quot;class&quot;:&quot;&quot;,&quot;count&quot;:&quot;1&quot;,&quot;legendonly&quot;:&quot;&quot;,&quot;readonly&quot;:&quot;&quot;,&quot;score&quot;:&quot;5&quot;,&quot;starsonly&quot;:&quot;&quot;,&quot;best&quot;:&quot;5&quot;,&quot;gap&quot;:&quot;4&quot;,&quot;greet&quot;:&quot;Rate this product&quot;,&quot;legend&quot;:&quot;5\/5 - (1 vote)&quot;,&quot;size&quot;:&quot;24&quot;,&quot;title&quot;:&quot;Program Design Project 3 Solved&quot;,&quot;width&quot;:&quot;138&quot;,&quot;_legend&quot;:&quot;{score}\/{best} - ({count} {votes})&quot;,&quot;font_factor&quot;:&quot;1.25&quot;}">

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
            5/5 - (1 vote)    </div>
    </div>
1.&nbsp; Write a program to create a randomized integer array of randomized length. The program will start with creating a random integer in the range of 8 to 15 for the length of the integer array, then for each array element, create a random integer in the range of 33 to 126 (ASCII values of printable characters except space), then display the corresponding ASCII

characters. For example, for the sample output below, the array of random integers generated

is: 63 47 86 95 110 60 68 97 101 59 39 48

Sample output:

?/V_nDae;'[

The program should include the following function where a is the array for the randomly generated values and n is the size of the array

void generate_values(int a[], int n);

1) Name your program ASCII_values.c

2) The main function creates a random number for the array length between 8 to 15, and declares the array, calls the random_values function, and then displays the array.

3) In the generate_values() function, use rand() function to generating random values in the range of 33 to 126.

4) To display an integer as a character, use “%c” format specifier in printf function.

5) To use the rand() and time function, you need to include &lt;stdlib.h&gt; and &lt;time.h&gt;.

How to use the rand() function to generate a random number:

1) With the help of rand () function, a number in range of lower to upper can be generated as num = (rand() % (upper – lower + 1)) + lower

2) rand() function generates the same sequence again and again every time the program runs. Use srand() function with time to set seed for rand() function so it generates different sequences of random numbers. Include the following statement at the beginning of the main function: srand(time(NULL));

Example runs:

Example output #1:

?/V_nDae;'[

NOT a strong password

Example output #2:

%~I+BI92aBM

A strong password

The program should include the following function. The function returns 1 if it is a strong password, otherwise returns 0.

int is_strong_password(int a[], int n);

1) Name your program password.c

2) The main function and display the result.

Before you submit

1. Compile both programs with –Wall. –Wall shows the warnings by the compiler. Be sure it compiles on student cluster with no errors and no warnings.

gcc –Wall ASCII_values.c gcc –Wall password.c

2. Be sure your Unix source file is read &amp; write protected. Change Unix file permission on Unix:

chmod 600 ASCII_values.c chmod 600 password.c

3. Test your programs multiple times to check its correctness. There are no testing scripts for this project since the arrays are generated randomly.

4. Submit ASCII_values.c and password.c on Canvas.

Grading

Total points: 100 (50 points each problem)

1. A program that does not compile will result in a zero.

3. Commenting and style 15%

4. Functionality 80% (including functions implemented as required)

Programming Style Guidelines

The major purpose of programming style guidelines is to make programs easy to read and understand. Good programming style helps make it possible for a person knowledgeable in the application area to quickly read a program and understand how it works.

1. Your program should begin with a comment that briefly summarizes what it does. This comment should also include your name.

2. In most cases, a function should have a brief comment above its definition describing what it does. Other than that, comments should be written only needed in order for a reader to understand what is happening.

3. Variable names and function names should be sufficiently descriptive that a knowledgeable reader can easily understand what the variable means and what the function does. If this is not possible, comments should be added to make the meaning clear.

4. Use consistent indentation to emphasize block structure.

5. Full line comments inside function bodies should conform to the indentation of the code where they appear.

6. Macro definitions (#define) should be used for defining symbolic names for numeric constants. For example: #define PI 3.141592

7. Use names of moderate length for variables. Most names should be between 2 and 12 letters long.

8. Use underscores to make compound names easier to read: tot_vol or total_volumn is clearer than totalvolumn.
