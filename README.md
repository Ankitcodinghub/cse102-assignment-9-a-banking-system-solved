# cse102-assignment-9-a-banking-system-solved
**TO GET THIS SOLUTION VISIT:** [CSE102 Assignment 9-A banking system Solved](https://www.ankitcodinghub.com/product/cse102-assignment-9-solved-2/)


---

📩 **If you need this solution or have special requests:** **Email:** ankitcoding@gmail.com  
📱 **WhatsApp:** +1 419 877 7882  
📄 **Get a quote instantly using this form:** [Ask Homework Questions](https://www.ankitcodinghub.com/services/ask-homework-questions/)

*We deliver fast, professional, and affordable academic help.*

---

<h2>Description</h2>



<div class="kk-star-ratings kksr-auto kksr-align-center kksr-valign-top" data-payload="{&quot;align&quot;:&quot;center&quot;,&quot;id&quot;:&quot;101994&quot;,&quot;slug&quot;:&quot;default&quot;,&quot;valign&quot;:&quot;top&quot;,&quot;ignore&quot;:&quot;&quot;,&quot;reference&quot;:&quot;auto&quot;,&quot;class&quot;:&quot;&quot;,&quot;count&quot;:&quot;1&quot;,&quot;legendonly&quot;:&quot;&quot;,&quot;readonly&quot;:&quot;&quot;,&quot;score&quot;:&quot;5&quot;,&quot;starsonly&quot;:&quot;&quot;,&quot;best&quot;:&quot;5&quot;,&quot;gap&quot;:&quot;4&quot;,&quot;greet&quot;:&quot;Rate this product&quot;,&quot;legend&quot;:&quot;5\/5 - (1 vote)&quot;,&quot;size&quot;:&quot;24&quot;,&quot;title&quot;:&quot;CSE102 Assignment 9-A banking system Solved&quot;,&quot;width&quot;:&quot;138&quot;,&quot;_legend&quot;:&quot;{score}\/{best} - ({count} {votes})&quot;,&quot;font_factor&quot;:&quot;1.25&quot;}">

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
<div class="page" title="Page 1">
<div class="layoutArea">
<div class="column">
Homework Description: In this homework, you will implement a banking system. This homework will

be implemented by using Structs, Unions, Recursive functions and File operations in C. You need 2 unions and 1 struct type. These are;

</div>
</div>
<div class="section">
<div class="layoutArea">
<div class="column">
<pre>union Person
{
</pre>
<pre>    char name[50];
    char address[50];
    int phone;
</pre>
};

union Loan {

<pre>    float amount;
    float interestRate;
    int period;
</pre>
};

<pre>struct BankAccount
{
</pre>
<pre>    union Person Customer;
</pre>
<pre>    union Loan Loans[3];
};
</pre>
</div>
</div>
</div>
<div class="layoutArea">
<div class="column">
The first union structure is Person. This union has to keep personal information. This value may change, in the image, it is for example purposes only. You can add extra information. The second union is credit. Here, it should keep the amount of the loan, the interest rate and the number of periods. The struct is BankAccount. Inside the struct, you have to keep Person and Loan of type union. You will open bank accounts within the system and assign loans to customers by calculating loans. Each customer can only have 3 loans. Banking system keeps maximum 50 customer in same time. Each fields are will be get from user input with using command line.

</div>
</div>
</div>
<div class="page" title="Page 2">
<div class="layoutArea">
<div class="column">
Function prototypes are :

</div>
</div>
<div class="layoutArea">
<div class="column">
listCustomers()

addCustomer ()

newLoan ()

calculateLoan(float amount, int period, float interestRate);

getReport();

You have to use a recursive function when calculating the loan. You are not allowed to use the pow() function. The formula for calculating the loan is below.

𝑳𝒐𝒂𝒏 𝑭𝒐𝒓𝒎𝒖𝒍𝒂 = 𝑨𝒎𝒐𝒖𝒏𝒕 ∗ ( 𝟏 + 𝒊𝒏𝒕𝒆𝒓𝒆𝒔𝒕𝑹𝒂𝒕𝒆)𝒑𝒆𝒓𝒊𝒐𝒅

In the report section, you have to print out 2 reports. These are the Customer list and Loan detail. You must keep all customers in the customers.txt file. When requesting this report, you must read customers.txt file and print the customers to the screen. When printing a loan detail of a customer, you need to print the total value of that loan and each period one by one as in the example. Not all states are shown in the expected outputs, but you have to check all states and incorrect entries for each step. You can specify the function types according to your needs. Unless the program exit option is selected, it has to return to the menu after each operation. Remember, the list in option 1 has to print the customers in the struct to the screen. The report menu in the 4th option has to print the customers and loans it reads from the file on the screen.

Expected Outputs

</div>
</div>
</div>
<div class="page" title="Page 3">
<div class="layoutArea">
<div class="column">
General Rules:

<ol>
<li>Obey the style guidelines.</li>
<li>Do not change the provided function prototypes (you will not get any credits).</li>
<li>The program must be developed on Ubuntu using GCC compiler (version provided in class),compilation problems due to the use of another OS or compiler is your responsibility (you will
not get any credits).
</li>
<li>Your program should work as expected. Do not expect partial credit if your code works onlyin some cases but not in all cases as expected.</li>
<li>Hand in your work using the appropriate class Teams assignment site.</li>
<li>No late submissions will be accepted.</li>
<li>Pack this directory into a zip file named 20180000001_X_Z.zip</li>
<li>When unpacked as above in Ubuntu (version provided in class) it should allow executingthe following commands in a shell:

▪ “$make clean” removes everything except makefile, source code (.c) and other resource files (if any) – all compiling results and intermediate files should be removed (except results.txt). ▪ “$make compile” should compile the code.

▪ “$make run” should run the code along with any parameters needed.</li>
</ol>
</div>
</div>
</div>
