# cmsc403-assignment-6-solved
**TO GET THIS SOLUTION VISIT:** [CMSC403 Assignment 6 Solved](https://www.ankitcodinghub.com/product/cmsc403-assignment-6-solved-2/)


---

📩 **If you need this solution or have special requests:** **Email:** ankitcoding@gmail.com  
📱 **WhatsApp:** +1 419 877 7882  
📄 **Get a quote instantly using this form:** [Ask Homework Questions](https://www.ankitcodinghub.com/services/ask-homework-questions/)

*We deliver fast, professional, and affordable academic help.*

---

<h2>Description</h2>



<div class="kk-star-ratings kksr-auto kksr-align-center kksr-valign-top" data-payload="{&quot;align&quot;:&quot;center&quot;,&quot;id&quot;:&quot;113768&quot;,&quot;slug&quot;:&quot;default&quot;,&quot;valign&quot;:&quot;top&quot;,&quot;ignore&quot;:&quot;&quot;,&quot;reference&quot;:&quot;auto&quot;,&quot;class&quot;:&quot;&quot;,&quot;count&quot;:&quot;1&quot;,&quot;legendonly&quot;:&quot;&quot;,&quot;readonly&quot;:&quot;&quot;,&quot;score&quot;:&quot;5&quot;,&quot;starsonly&quot;:&quot;&quot;,&quot;best&quot;:&quot;5&quot;,&quot;gap&quot;:&quot;4&quot;,&quot;greet&quot;:&quot;Rate this product&quot;,&quot;legend&quot;:&quot;5\/5 - (1 vote)&quot;,&quot;size&quot;:&quot;24&quot;,&quot;title&quot;:&quot;CMSC403  Assignment 6 Solved&quot;,&quot;width&quot;:&quot;138&quot;,&quot;_legend&quot;:&quot;{score}\/{best} - ({count} {votes})&quot;,&quot;font_factor&quot;:&quot;1.25&quot;}">

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
Define the following Common Lisp functions and macros. Please save your common lisp code in a file named Assignment6.lisp and upload the file to Gradescope when the assignment is complete. A few notes about the assignment:

• Assignment6.lisp is expected to contain only the methods described in this assignment manual. (load “Assignment6.lisp”) should return T and print no other information to the console.

• Parameter names can be arbitrary. I gave the parameters names to identify them in the assignment manual but your implementation does not need to use those specific names.

o Function and macro names, on the other hand, must be exactly as specified.

• Parameters must be in the order they are listed in the assignment manual.

• Functions are expected to return values, not print values to the console.

o Functions should not print any information to the console when executed.

• Do not use defun inside of a function body.

• Do not define any global variables with defvar. For local variables inside functions, use let and let* blocks.

• Assume all inputs are valid, you do not need to do any parameter validation in your functions.

• You are allowed (and encouraged) to utilize methods defined in Common Lisp which have not been discussed in class. The documentation for Common Lisp can be found at http://clhs.lisp.se/ (I advise using Google to search the site. Although the information is good, the web design aspect leaves much to be desired)

• You must comment your Common Lisp code. The ; character is used to denote comments.

• You cannot use the setq special operator, nor the setf, delete, or any derivatives of the setq special operator in any of your functions. These are destructive operations and go against the functional paradigm described in class.

• I highly recommend against using looping macros and online compilers for the development of this assignment, historically they have caused significant confusion.

1. [5 points] Write a Common Lisp function named myList which creates the following list and returns it

(4 (7 22) “art” (“math” (8) 99) 100)

3. [10 points] Write a Common Lisp function named union- which takes two list parameters. union- returns a single list which contains the separate unique entities from both lists, with no duplication. You are not allowed to use the predefined union function for this function.

4. [10 points] Write a Common Lisp function named avg with a single parameter named aList. avg returns the average of all elements in aList. Assume all elements in aList are numbers. If given an empty list, avg should return NIL. The avg function must be tail recursive.

5. [15 points] Write a Common Lisp function named isType which takes a single parameter named dataType. isType will return an anonymous function which takes a single parameter and returns true if the parameters data type is the data type specified in dataType. Otherwise the anonymous function returns false.

6. [15 points] Write a Common Lisp function named taxCalculator with three parameters: limit, rate, and values. limit and rate will be numbers, values will be a list.

taxCalculator returns a list with the same elements and ordering of the values parameter EXCEPT every element which is greater than limit is multiplied by rate.

Assume that all elements of the values list are numbers.

BONUS: Make taxCalculator tail recursive +5 points

7. [20 points] Write a Common Lisp function named clean which takes two parameters: aFunc and aList. aFunc will be a function and aList a list. aFunc is expected to be a function which takes a single parameter and returns a boolean value. clean will return a list which contains all values in aList which, when passed to aFunc, return true. if aList contains sublists, clean should create a new sublist with only the values which return true when passed to aFunc

8. [15 points] Define a Common Lisp macro named threeWayBranch which takes three parameters, x y and toExecute. x and y will be numbers and toExecute a list with three sublists. The threeWayBranch macro will execute statements in toExecute’s first sublist if x &lt; y, the second sublist if x &gt; y, and the third sublist if x = y. Assume each of toExecute’s sublists contain an arbitrary number of statements.
