# comp210-assignment-1-solved
**TO GET THIS SOLUTION VISIT:** [Comp210 Assignment 1 Solved](https://mantutor.com/product/comp210-a1-solved/)


---

**For Custom/Order Solutions:** **Email:** mantutorcodes@gmail.com  

*We deliver quick, professional, and affordable assignment help.*

---

<h2>Description</h2>



<div class="kk-star-ratings kksr-auto kksr-align-center kksr-valign-top" data-payload="{&quot;align&quot;:&quot;center&quot;,&quot;id&quot;:&quot;115086&quot;,&quot;slug&quot;:&quot;default&quot;,&quot;valign&quot;:&quot;top&quot;,&quot;ignore&quot;:&quot;&quot;,&quot;reference&quot;:&quot;auto&quot;,&quot;class&quot;:&quot;&quot;,&quot;count&quot;:&quot;2&quot;,&quot;legendonly&quot;:&quot;&quot;,&quot;readonly&quot;:&quot;&quot;,&quot;score&quot;:&quot;5&quot;,&quot;starsonly&quot;:&quot;&quot;,&quot;best&quot;:&quot;5&quot;,&quot;gap&quot;:&quot;4&quot;,&quot;greet&quot;:&quot;Rate this product&quot;,&quot;legend&quot;:&quot;5\/5 - (2 votes)&quot;,&quot;size&quot;:&quot;24&quot;,&quot;title&quot;:&quot;Comp210 Assignment 1 Solved&quot;,&quot;width&quot;:&quot;138&quot;,&quot;_legend&quot;:&quot;{score}\/{best} - ({count} {votes})&quot;,&quot;font_factor&quot;:&quot;1.25&quot;}">

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
Congratulations! If you’re seeing this, then presumably you’ve managed to: * Install Java * Install IntelliJ IDEA * Install Git * Created a GitHub account * Accepted the A1 assignment link.

If you haven’t done one or more of those things, please do.

This repository should be a “private” repository and access to it is limited to yourself, KMP, and the COMP 210 team.

Now it’s time to create an IntelliJ project based on this repository. From the IntelliJ splash screen, simply select “Get From Version Control” and then provide the git clone URL for this repository. Or, if you are not on the IntelliJ splash screen, select menu item File -&gt; New -&gt; Project From Version Control… and again, provide the git clone URL for this repository. Demonstrated in this YouTube video: https://youtu.be/xx9GLxo6Y9M

The first thing we’ll do is make sure you’re able to run a program in IntelliJ and provide input from the keyboard to that program. Follow this video and follow along: https://youtu.be/S2caecQkWSI

<iframe title="Submitting To GradeScope" width="980" height="551" src="https://www.youtube.com/embed/jVx2rCffVf0?feature=oembed" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen=""></iframe>

Did you get your first point of the assignment? If yes, then congratulations. If not, better go work it out eventually, but you could also keep going with the assignment.

Now things are set up, here is the rest of the assignment.

Scanner

This assignment requires you to make use of a Scanner object. You can read the documentation for Scanner here: https://docs.oracle.com/en/java/javase/12/docs/api/java.base/java/util/Scanner.html

A Scanner object is associated with a source of input. In our case, this will be keyboard input from the console. By default, a Scanner object will parse input as whitespace-separated tokens and provides methods for parsing the next available token as a particular type.

For example, the method next() will retrieve the next token (i.e., word) as a String. Similarly, the method nextInt() interprets and returns the value of the next token as an integer while nextDouble() will interpret the next token as a double value. For this assignment, you shouldn’t have to use any Scanner methods other than next(), nextInt(), and nextDouble(). In particular, you should avoid using nextLine(). Do not assume that the input is organized into lines. All of the input could be on a single line or each word might be on a different line or something in between. Do not make any assumptions about the input being organized into lines.

For this assignment, you can assume that the input will always be valid and conform to the description below. In other words, you do not have to worry about validating the input or being able to deal with unexpected input.

A1Novice

This program will read in data that represents shopping orders from a number of customers and report the total amount spent on a per customer basis. The input provided will have the following form:

The first input will be an integer indicating the total number of customers.

Then, for each customer, the input will be comprised of:

The first name of the customer

The last name of the customer

The number of items bought by the customer.

For each item bought, the input will then contain:

An integer quantity of the item bought

The name of the item (you can assume these will be single words) The price of the item as a double

For each customer, your program should print one line of ouptut in the following form:

F. LAST: TOTAL

Where F. represents the first letter initial of the first name of the customer, LAST represents the last name of the customer, and TOTAL is the total cost of the items purchased to two decimal places.

For example, the following input:

3 Carrie Brownstein 3 2 Banana 0.75 1 Orange 1.25 2 Milk 3.15 Corin Tucker 2 3 Banana 0.75 2 Sponge 1.15 Janet Weiss 1 5 Salami 2.50

Should produce the following output:

C. Brownstein: 9.05 C. Tucker: 4.55 J. Weiss: 12.50

A1Adept

This program will also read in shopping order data but now provided in a slightly different form and will produce output that reports the customers that were the biggest and smallets spenders as well as the average bill for all customers.

Input to the program will have the following form:

An integer count of the number of items in the store.

Then for each item in the store…

The name of each item (a single word)

The price of the item

An integer count of the number of customers Then for each customer…

The first name of the customer

The last name of the customer

An integer count of the number of items the customer bought.

For each of the items bought… The quantity of the item bought The name of the item

The output of the program should be exactly three lines in the following form:

Biggest: FIRST LAST (AMOUNT) Smallest: FIRST LAST (AMOUNT) Average: AVERAGE

… where FIRST and LAST are the first and last names of the biggest and smallest spenders as appropriate, AMOUNT is the amount spent, and AVERAGE is the average amount spent. For example, the following input:

6 Apple 0.25 Banana 0.75 Milk 3.15 Orange 1.25 Salami 2.50 Sponge 1.15 3 Carrie Brownstein 3 2 Banana 1 Orange 2 Milk Corin Tucker 2 3 Banana 2 Sponge Janet Weiss 1 5 Salami

Should produce the following output:

Biggest: Janet Weiss (12.50) Smallest: Corin Tucker (4.55) Average: 8.70

A1Jedi

This program will read in data with the same form as A1Adept and as output will report for each item how many different customers bought that item and the total quantity of the item bought by all customers. Each item should be reported in the same order as specified in the beginning of the input. Each report line should have the form:

NUMBER customers bought TOTAL ITEM

… where NUMBER is the number of customers that bought the item, TOTAL is the total quantity of the item bought by all customers and ITEM is the item name.

If no customers bought an item, then the report for that item should be in the form:

No customers bought ITEM

For example, the same input provided as an example for A1Adept above should produce the following output for A1Jedi:

No customers bought Apple 2 customers bought 5 Banana 1 customers bought 2 Milk 1 customers bought 1 Orange 1 customers bought 5 Salami 1 customers bought 2 Sponge

Hints

In order to convert a double (let’s call it “value”) to a String with two decimal places, use the following expression:

String.format(“%.2f, value)

6 Apple 0.25 Banana 0.75 Milk 3.15 Orange 1.25 Salami 2.50 Sponge 1.15 3 Carrie Brownstein 5 1 Banana 1 Orange 1 Milk 1 Banana 1 Milk Corin Tucker 3 1 Banana 2 Sponge 2 Banana Janet Weiss 3 2 Salami 2 Salami 1 Salami

You should also be sure to only use next, nextInt, and nextDouble as methods of the Scanner object in order to read the next expected input word as either a String, int, or double without trying to process the input as lines. You should not assume any sort of line structure to the input. In other words, the following is a valid equivalent to the example input provided above:

6 Apple 0.25 Banana 0.75 Milk 3.15 Orange 1.25 Salami 2.50 Sponge 1.15 3 Carrie Brownstein 5 1 Banana 1 Orange

1 Milk 1 Banana 1 Milk Corin Tucker 3 1 Banana 2 Sponge 2 Banana Janet Weiss 3 2 Salami 2 Salami 1 Salami
