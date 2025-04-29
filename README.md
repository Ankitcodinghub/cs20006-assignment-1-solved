# cs20006-assignment-1-solved
**TO GET THIS SOLUTION VISIT:** [CS20006 Assignment 1 Solved](https://www.ankitcodinghub.com/product/software-engineering-cs20006-solved/)


---

📩 **If you need this solution or have special requests:** **Email:** ankitcoding@gmail.com  
📱 **WhatsApp:** +1 419 877 7882  
📄 **Get a quote instantly using this form:** [Ask Homework Questions](https://www.ankitcodinghub.com/services/ask-homework-questions/)

*We deliver fast, professional, and affordable academic help.*

---

<h2>Description</h2>



<div class="kk-star-ratings kksr-auto kksr-align-center kksr-valign-top" data-payload="{&quot;align&quot;:&quot;center&quot;,&quot;id&quot;:&quot;116481&quot;,&quot;slug&quot;:&quot;default&quot;,&quot;valign&quot;:&quot;top&quot;,&quot;ignore&quot;:&quot;&quot;,&quot;reference&quot;:&quot;auto&quot;,&quot;class&quot;:&quot;&quot;,&quot;count&quot;:&quot;2&quot;,&quot;legendonly&quot;:&quot;&quot;,&quot;readonly&quot;:&quot;&quot;,&quot;score&quot;:&quot;5&quot;,&quot;starsonly&quot;:&quot;&quot;,&quot;best&quot;:&quot;5&quot;,&quot;gap&quot;:&quot;4&quot;,&quot;greet&quot;:&quot;Rate this product&quot;,&quot;legend&quot;:&quot;5\/5 - (2 votes)&quot;,&quot;size&quot;:&quot;24&quot;,&quot;title&quot;:&quot;CS20006 Assignment 1 Solved&quot;,&quot;width&quot;:&quot;138&quot;,&quot;_legend&quot;:&quot;{score}\/{best} - ({count} {votes})&quot;,&quot;font_factor&quot;:&quot;1.25&quot;}">

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
Instructions: Please solve the questions using pen and paper and scan the images. Every image should contain your roll number and name.

1. Consider the following program which should obviously print Match.

#include &lt;iostream&gt; #include &lt;cmath&gt; using namespace std; #define sqr(x) ((x) * (x))

int main() { double a = 4.0*atan(1.0); // pi double b = sqrt(a); // square-root of pi

if (a == sqr(b)) // pi is equal to

// square of square-root of pi?

cout &lt;&lt; “Match” &lt;&lt; endl;

else cout &lt;&lt; “Mis-Match” &lt;&lt; endl;

return 0;

}

However, on Visual C++ 64-bit compiler, it prints Mis-Match. Identify the bug and fix it. [1 + 1 = 2]

Write an appropriate guideline to avoid such bugs and improve the quality

of the code. [1]

2. What is the output of the following program? [1]

#include &lt;iostream&gt; using namespace std;

int main() { int *p = new int(5);

if (p = 0) cout &lt;&lt; “No Value” &lt;&lt; endl; else

cout &lt;&lt; *p &lt;&lt; endl;

return 0;

}

Is it what the developer intended? If yes, justify the thoughts of the developer. If no, find the bug in the program and fix it. [1]

Write an appropriate guideline to avoid such bugs and improve the quality of the code. [1]

3. Consider the following program:

#include &lt;iostream&gt; using namespace std;

int rem(int n, int r) {

return n % r;

}

int main() {

int n = 15, r = 0; // Line 1

// int n, r; // Line 2

// cin &gt;&gt; n &gt;&gt; r; // Line 3

if (r == 0 || rem(n, r)) cout &lt;&lt; “True” &lt;&lt; endl; else cout &lt;&lt; “False” &lt;&lt; endl;

if (rem(n, r) || r == 0) cout &lt;&lt; “True” &lt;&lt; endl; else cout &lt;&lt; “False” &lt;&lt; endl;

return 0;

}

While using Visual C++ 64-bit compiler, the output is as follows:

Build Type Output

Debug (Un-optimized) True

Un-handled Floating Point Exception

Release (Optimized) True

True

Now let us comment Line 1 and un-comment Line 2 &amp; Line 3. The output changes to the following while we input 15 for n and 0 for r (as was initialized in Line 1:

Build Type Output

Debug (Un-optimized) True

Un-handled Floating Point Exception

Release (Optimized) True

Un-handled Floating Point Exception

[2 + 2 = 4]

Write an appropriate guideline to avoid such bugs and improve the quality of the code. [1]

Function Behaviour Justification &amp;

Name Comments

f1()

f2()

…

f6()

Finally, based on the observations above, formulate guidelines to maintain a good quality of code. [2]

#include &lt;iostream&gt; #include &lt;cstring&gt; using namespace std;

void f1() {

char * str = “Bat”; cout &lt;&lt; str &lt;&lt; endl; str[0] = ’C’; cout &lt;&lt; str &lt;&lt; endl; str = “Rat”; cout &lt;&lt; str &lt;&lt; endl; cout &lt;&lt; endl;

}

void f2() {

const char * str = “Bat”; cout &lt;&lt; str &lt;&lt; endl; str[0] = ’C’; cout &lt;&lt; str &lt;&lt; endl; str = “Rat”; cout &lt;&lt; str &lt;&lt; endl; cout &lt;&lt; endl;

}

void f3() {

char * const str = “Bat”; cout &lt;&lt; str &lt;&lt; endl; str[0] = ’C’; cout &lt;&lt; str &lt;&lt; endl; str = “Rat”; cout &lt;&lt; str &lt;&lt; endl; cout &lt;&lt; endl;

}

void f4() { char * str = strdup(“Bat”); cout &lt;&lt; str &lt;&lt; endl; str[0] = ’C’; cout &lt;&lt; str &lt;&lt; endl; str = strdup(“Rat”); cout &lt;&lt; str &lt;&lt; endl; cout &lt;&lt; endl;

}

void f5() { const char * str = strdup(“Bat”); cout &lt;&lt; str &lt;&lt; endl; str[0] = ’C’; cout &lt;&lt; str &lt;&lt; endl; str = strdup(“Rat”); cout &lt;&lt; str &lt;&lt; endl; cout &lt;&lt; endl;

}

void f6() { char * const str = strdup(“Bat”); cout &lt;&lt; str &lt;&lt; endl; str[0] = ’C’; cout &lt;&lt; str &lt;&lt; endl; str = strdup(“Rat”); cout &lt;&lt; str &lt;&lt; endl; cout &lt;&lt; endl;

}

int main() { f1(); f2(); f3(); f4(); f5(); f(6);

return 0;

}

[0.5 * 24 = 12]

Function Behaviour Justification &amp;

Name Comments

Line 01

Line 02

…

Line 24

Finally, based on the observations above, formulate guidelines to maintain a good quality of code. [2]

#include &lt;iostream&gt; #include &lt;cmath&gt; using namespace std;

int e(int x) { cout &lt;&lt; “x = ” &lt;&lt; x &lt;&lt; ” &amp;x = ” &lt;&lt; &amp;x &lt;&lt; endl;

return (x);

}

int f(int &amp;x) { cout &lt;&lt; “x = ” &lt;&lt; x &lt;&lt; ” &amp;x = ” &lt;&lt; &amp;x &lt;&lt; endl; return (x);

} int&amp; g(int x) { cout &lt;&lt; “x = ” &lt;&lt; x &lt;&lt; ” &amp;x = ” &lt;&lt; &amp;x &lt;&lt; endl;

return (x);

} int&amp; h(int &amp;x) { cout &lt;&lt; “x = ” &lt;&lt; x &lt;&lt; ” &amp;x = ” &lt;&lt; &amp;x &lt;&lt; endl; return (x);

}

int main() { int a = 10; cout &lt;&lt; “a = ” &lt;&lt; a &lt;&lt; ” &amp;a = ” &lt;&lt; &amp;a &lt;&lt; endl;

int&amp; rvv = e(a); // Line 01 int&amp; rrv = f(a); // Line 02 int&amp; rvr = g(a); // Line 03 int&amp; rrr = h(a); // Line 04

cout &lt;&lt; “rvv = ” &lt;&lt; rvv &lt;&lt; ” &amp;rvv = ” &lt;&lt; &amp;rvv &lt;&lt; endl; // Line 05 cout &lt;&lt; “rrv = ” &lt;&lt; rrv &lt;&lt; ” &amp;rrv = ” &lt;&lt; &amp;rrv &lt;&lt; endl; // Line 06 cout &lt;&lt; “rvr = ” &lt;&lt; rvr &lt;&lt; ” &amp;rvr = ” &lt;&lt; &amp;rvr &lt;&lt; endl; // Line 07 cout &lt;&lt; “rrr = ” &lt;&lt; rrr &lt;&lt; ” &amp;rrr = ” &lt;&lt; &amp;rrr &lt;&lt; endl; // Line 08

const int&amp; rvvc = e(a); // Line 09 const int&amp; rrvc = f(a); // Line 10 const int&amp; rvrc = g(a); // Line 11 const int&amp; rrrc = h(a); // Line 12

cout &lt;&lt; “rvvc = ” &lt;&lt; rvvc &lt;&lt; ” &amp;rvvc = ” &lt;&lt; &amp;rvvc &lt;&lt; endl; // Line 13 cout &lt;&lt; “rrvc = ” &lt;&lt; rrvc &lt;&lt; ” &amp;rrvc = ” &lt;&lt; &amp;rrvc &lt;&lt; endl; // Line 14 cout &lt;&lt; “rvrc = ” &lt;&lt; rvrc &lt;&lt; ” &amp;rvrc = ” &lt;&lt; &amp;rvrc &lt;&lt; endl; // Line 15 cout &lt;&lt; “rrrc = ” &lt;&lt; rrrc &lt;&lt; ” &amp;rrrc = ” &lt;&lt; &amp;rrrc &lt;&lt; endl; // Line 16

e(a) = 1; // Line 17 cout &lt;&lt; “a = ” &lt;&lt; a &lt;&lt; ” &amp;a = ” &lt;&lt; &amp;a &lt;&lt; endl; // Line 18 f(a) = 2; // Line 19 cout &lt;&lt; “a = ” &lt;&lt; a &lt;&lt; ” &amp;a = ” &lt;&lt; &amp;a &lt;&lt; endl; // Line 20 g(a) = 3; // Line 21 cout &lt;&lt; “a = ” &lt;&lt; a &lt;&lt; ” &amp;a = ” &lt;&lt; &amp;a &lt;&lt; endl; // Line 22 h(a) = 4; // Line 23 cout &lt;&lt; “a = ” &lt;&lt; a &lt;&lt; ” &amp;a = ” &lt;&lt; &amp;a &lt;&lt; endl; // Line 24

return 0;

}
