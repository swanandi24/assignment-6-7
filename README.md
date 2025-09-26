# assignment-6-7
Experiment 6 &amp; 7
Q1] code:
&lt;!DOCTYPE html&gt;
&lt;html&gt;
&lt;body&gt;

&lt;p id=&quot;exp61&quot;&gt;&lt;/p&gt;

&lt;script&gt;

let name = &quot;Swanandi&quot;;
let age = 17;
let isStudent = true;

let output61 = &quot;Name: &quot; + name + &quot;&lt;br&gt;&quot; +
&quot;Age: &quot; + age + &quot;&lt;br&gt;&quot; +
&quot;Is Student: &quot; + isStudent + &quot;&lt;br&gt;&quot; +
&quot;Type of name: &quot; + typeof name + &quot;&lt;br&gt;&quot; +
&quot;Type of age: &quot; + typeof age + &quot;&lt;br&gt;&quot; +
&quot;Type of isStudent: &quot; + typeof isStudent;

document.getElementById(&quot;exp61&quot;).innerHTML = output61;
&lt;/script&gt;
&lt;/body&gt;
&lt;/html&gt;

Output:
Name: Swanandi
Age: 17
Is Student: true
Type of name: string
Type of age: number
Type of isStudent: Boolean

Q2]
Code:
&lt;!DOCTYPE html&gt;
&lt;html&gt;
&lt;body&gt;

&lt;p id=&quot;exp62&quot;&gt;&lt;/p&gt;

&lt;script&gt;

let a = 15;
let b = 4;

let output62 = &quot;a = &quot; + a + &quot;, b = &quot; + b + &quot;&lt;br&gt;&quot; +
&quot;a + b = &quot; + (a + b) + &quot;&lt;br&gt;&quot; +
&quot;a - b = &quot; + (a - b) + &quot;&lt;br&gt;&quot; +
&quot;a * b = &quot; + (a * b) + &quot;&lt;br&gt;&quot; +
&quot;a / b = &quot; + (a / b) + &quot;&lt;br&gt;&quot; +
&quot;a % b = &quot; + (a % b);

document.getElementById(&quot;exp62&quot;).innerHTML = output62;

&lt;/script&gt;
&lt;/body&gt;
&lt;/html&gt;

Output:
a = 15, b = 4
a + b = 19
a - b = 11
a * b = 60
a / b = 3.75
a % b = 3

Q3]
Code:
&lt;!DOCTYPE html&gt;
&lt;html&gt;
&lt;body&gt;

&lt;p id=&quot;exp63&quot;&gt;&lt;/p&gt;

&lt;script&gt;

let num1 = 20;
let num2 = 5;
let operator = &quot;*&quot;;

let result;
if (operator === &quot;+&quot;) {
result = num1 + num2;
} else if (operator === &quot;-&quot;) {
result = num1 - num2;
} else if (operator === &quot;*&quot;) {
result = num1 * num2;
} else if (operator === &quot;/&quot;) {
result = num1 / num2;
} else {
result = &quot;Invalid operator!&quot;;
}

let output63 = num1 + &quot; &quot; + operator + &quot; &quot; + num2 + &quot; = &quot; + result;
document.getElementById(&quot;exp63&quot;).innerHTML = output63;
&lt;/script&gt;
&lt;/body&gt;
&lt;/html&gt;
Output:
20 * 5 = 100

Q4]
Code:
&lt;!DOCTYPE html&gt;
&lt;html&gt;
&lt;body&gt;

&lt;h2&gt;Voting Eligibility Check&lt;/h2&gt;

&lt;p id=&quot;result&quot;&gt;&lt;/p&gt;

&lt;script&gt;
function checkEligibility() {
let age = 21;

if (age &gt;= 18) {
document.getElementById(&quot;result&quot;).innerHTML = &quot;Eligible to vote&quot;;
} else {
document.getElementById(&quot;result&quot;).innerHTML = &quot;Not eligible to vote&quot;;
}
}

checkEligibility();
&lt;/script&gt;

&lt;/body&gt;
&lt;/html&gt;

Output:
Voting Eligibility Check
Eligible to vote

Q5]
Code:
&lt;!DOCTYPE html&gt;
&lt;html&gt;
&lt;body&gt;

&lt;h2&gt;Grading System&lt;/h2&gt;

&lt;p id=&quot;grade&quot;&gt;&lt;/p&gt;

&lt;script&gt;
let marks = 82;
let grade;

if (marks &gt;= 90) {
grade = &quot;Grade A&quot;;
} else if (marks &gt;= 75) {
grade = &quot;Grade B&quot;;
} else if (marks &gt;= 50) {
grade = &quot;Grade C&quot;;
} else {
grade = &quot;Fail&quot;;
}

document.getElementById(&quot;grade&quot;).innerHTML = &quot;Marks: &quot; + marks + &quot; → &quot; + grade;
&lt;/script&gt;

&lt;/body&gt;
&lt;/html&gt;

Output:
Grading System
Marks: 82 → Grade B

Q6]
Code:
&lt;!DOCTYPE html&gt;
&lt;html&gt;
&lt;body&gt;

&lt;h2&gt;Day of the Week&lt;/h2&gt;

&lt;p id=&quot;day&quot;&gt;&lt;/p&gt;

&lt;script&gt;
let num = 4;
let day;

switch (num) {
case 1: day = &quot;Monday&quot;; break;
case 2: day = &quot;Tuesday&quot;; break;
case 3: day = &quot;Wednesday&quot;; break;
case 4: day = &quot;Thursday&quot;; break;
case 5: day = &quot;Friday&quot;; break;
case 6: day = &quot;Saturday&quot;; break;
case 7: day = &quot;Sunday&quot;; break;
default: day = &quot;Invalid Input&quot;;
}

document.getElementById(&quot;day&quot;).innerHTML = &quot;Number: &quot; + num + &quot; → &quot; + day;
&lt;/script&gt;

&lt;/body&gt;
&lt;/html&gt;

Output:
Day of the Week
Number: 4 → Thursday

Q7]
1]
Code:
&lt;!DOCTYPE html&gt;
&lt;html&gt;
&lt;body&gt;

&lt;h2&gt;Even or Odd &lt;/h2&gt;

&lt;p id=&quot;evenOdd&quot;&gt;&lt;/p&gt;

&lt;script&gt;
let n = 15;
if (n % 2 === 0) {
document.getElementById(&quot;evenOdd&quot;).innerHTML = n + &quot; is Even&quot;;
} else {
document.getElementById(&quot;evenOdd&quot;).innerHTML = n + &quot; is Odd&quot;;
}

&lt;/script&gt;

&lt;/body&gt;
&lt;/html&gt;

Output:
Even or Odd
15 is Odd

2]
Code:
&lt;!DOCTYPE html&gt;
&lt;html&gt;
&lt;body&gt;

&lt;h2&gt;Largest Number&lt;/h2&gt;

&lt;p id=&quot;largest&quot;&gt;&lt;/p&gt;

&lt;script&gt;
let a = 25, b = 42, c = 37;
let largest;

if (a &gt;= b &amp;&amp; a &gt;= c) {
largest = a;
} else if (b &gt;= a &amp;&amp; b &gt;= c) {
largest = b;
} else {
largest = c;
}

document.getElementById(&quot;largest&quot;).innerHTML =
&quot;Numbers: &quot; + a + &quot;, &quot; + b + &quot;, &quot; + c + &quot; → Largest = &quot; + largest;
&lt;/script&gt;

&lt;/body&gt;
&lt;/html&gt;

Output:
Largest Number
Numbers: 25, 42, 37 → Largest = 42
