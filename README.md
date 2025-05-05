# j-j-accounting-firm-cpp-program-solved
**TO GET THIS SOLUTION VISIT:** [J&J accounting firm CPP program Solved](https://www.ankitcodinghub.com/product/jj-accounting-firm-cpp-program-solved/)


---

📩 **If you need this solution or have special requests:** **Email:** ankitcoding@gmail.com  
📱 **WhatsApp:** +1 419 877 7882  
📄 **Get a quote instantly using this form:** [Ask Homework Questions](https://www.ankitcodinghub.com/services/ask-homework-questions/)

*We deliver fast, professional, and affordable academic help.*

---

<h2>Description</h2>



<div class="kk-star-ratings kksr-auto kksr-align-center kksr-valign-top" data-payload="{&quot;align&quot;:&quot;center&quot;,&quot;id&quot;:&quot;7482&quot;,&quot;slug&quot;:&quot;default&quot;,&quot;valign&quot;:&quot;top&quot;,&quot;ignore&quot;:&quot;&quot;,&quot;reference&quot;:&quot;auto&quot;,&quot;class&quot;:&quot;&quot;,&quot;count&quot;:&quot;1&quot;,&quot;legendonly&quot;:&quot;&quot;,&quot;readonly&quot;:&quot;&quot;,&quot;score&quot;:&quot;5&quot;,&quot;starsonly&quot;:&quot;&quot;,&quot;best&quot;:&quot;5&quot;,&quot;gap&quot;:&quot;4&quot;,&quot;greet&quot;:&quot;Rate this product&quot;,&quot;legend&quot;:&quot;5\/5 - (1 vote)&quot;,&quot;size&quot;:&quot;24&quot;,&quot;title&quot;:&quot;J\u0026amp;J accounting firm CPP program Solved&quot;,&quot;width&quot;:&quot;138&quot;,&quot;_legend&quot;:&quot;{score}\/{best} - ({count} {votes})&quot;,&quot;font_factor&quot;:&quot;1.25&quot;}">

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
During the tax season, every Friday, the J&amp;J accounting firm provides assistance to people who prepare their own tax returns. Their charges are as follows:

If a person has low income (&lt;= 25,000) and the consulting time is less than or equal to 30 minutes, there are no charges; otherwise, the service charges are 40% of the regular hourly rate for the time over 30 minutes.

For others, if the consulting time is less than or equal to 20 minutes, there are no service charges; otherwise, service charges are 70% of the regular hourly rate for the time over 20 minutes.

(For example, suppose that a person has low income and spent 1 hour and 15 minutes, and the hourly rate is $70.00. Then the billing amount is 70.00 * 0.40 * (45 / 60) = $21.00.)

Write a program in C++ that prompts the user to enter the hourly rate, the total consulting time, and whether the person has low income. The program should output the billing amount. Your program must contain a function that takes as input the hourly rate, the total consulting time, and a value indicating whether the person has low income. The function should return the billing amount. Your program may prompt the user to enter the consulting time in minutes. Below is the code i have at the moment. I keep getting a “timed out” message on the testcase i am trying to pass it through. The subject is over User Defined Functions..

#include&lt;iostream&gt;

#include &lt;iomanip&gt;

using namespace std;

double calculateBill(int income, int consultingMinutes, double hourlyRate);

int main()

{

int income, consultingMinutes;

double hourlyRate;

cout &lt;&lt; “Please enter the clients income: $” ;

cin &gt;&gt; income; cout &lt;&lt; “Please enter the consulting time in minutes: “;

cin &gt;&gt; consultingMinutes;

cout &lt;&lt; “Please enter the hourly rate: $”;

cin &gt;&gt; hourlyRate; cout &lt;&lt; fixed &lt;&lt; showpoint &lt;&lt; setprecision(2);

cout &lt;&lt; “Your total bill ammount comes to: $” &lt;&lt; calculateBill(income, consultingMinutes, hourlyRate) &lt;&lt; endl;

return 0;

}

double calculateBill(int income, int consultingMinutes, double hourlyRate)

{

if (income &lt;= 25000) { if (consultingMinutes &lt;= 30) return 0; else return hourlyRate * 0.40 * ((consultingMinutes – 30) / 60);

}

else { if (consultingMinutes &lt;= 20) return 0;

else return hourlyRate * 0.70 * ((consultingMinutes – 20) / 60);

}

}
