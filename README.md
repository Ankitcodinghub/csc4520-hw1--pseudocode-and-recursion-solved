# csc4520-hw1--pseudocode-and-recursion-solved
**TO GET THIS SOLUTION VISIT:** [CSC4520 HW1- Pseudocode and Recursion Solved](https://www.ankitcodinghub.com/product/csc4520-hw1-pseudocode-and-recursion-solved-2/)


---

📩 **If you need this solution or have special requests:** **Email:** ankitcoding@gmail.com  
📱 **WhatsApp:** +1 419 877 7882  
📄 **Get a quote instantly using this form:** [Ask Homework Questions](https://www.ankitcodinghub.com/services/ask-homework-questions/)

*We deliver fast, professional, and affordable academic help.*

---

<h2>Description</h2>



<div class="kk-star-ratings kksr-auto kksr-align-center kksr-valign-top" data-payload="{&quot;align&quot;:&quot;center&quot;,&quot;id&quot;:&quot;114118&quot;,&quot;slug&quot;:&quot;default&quot;,&quot;valign&quot;:&quot;top&quot;,&quot;ignore&quot;:&quot;&quot;,&quot;reference&quot;:&quot;auto&quot;,&quot;class&quot;:&quot;&quot;,&quot;count&quot;:&quot;1&quot;,&quot;legendonly&quot;:&quot;&quot;,&quot;readonly&quot;:&quot;&quot;,&quot;score&quot;:&quot;5&quot;,&quot;starsonly&quot;:&quot;&quot;,&quot;best&quot;:&quot;5&quot;,&quot;gap&quot;:&quot;4&quot;,&quot;greet&quot;:&quot;Rate this product&quot;,&quot;legend&quot;:&quot;5\/5 - (1 vote)&quot;,&quot;size&quot;:&quot;24&quot;,&quot;title&quot;:&quot;CSC4520  HW1- Pseudocode and Recursion Solved&quot;,&quot;width&quot;:&quot;138&quot;,&quot;_legend&quot;:&quot;{score}\/{best} - ({count} {votes})&quot;,&quot;font_factor&quot;:&quot;1.25&quot;}">

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
In order to complete the coding portions of this assignment, you must make commits of your code. We will take the latest commit as your “final submission”.

Grading and Corrections

Java Language API

Focus on Algorithms’ details, not Java Language. Runnable, correctness, efficiency.

(well organized, easy to read, not in a mass)

Showing Your Work

1. You should add comments that explain the key ideas behind your approach.

Q1: Find Missing Number (2 points)

Convert the following pseudocode algorithm into Java. You’ll find example tests within the main method to ensure you’re headed in the right direction. Make sure you understand each example.

algorithm findMissing

Input: integer array A of length N where each element is distinct and in the range [0, N]

Output: integer x where x is in the range [0, N], but not in A

s = the sum of all numbers in A return (N(N+1))/2 – s

Q2: TwoSum (Fast) (3 points)

public static int[] twoSumFast(int[] arr, int target) {

HashSet&lt;Integer&gt; seen = new HashSet&lt;&gt;(); for (int j = 0; j &lt; arr.length; j++) {

int otherAddend = target – arr[j]; if (seen.contains(otherAddend)) { for (int i = 0; i &lt; arr.length; i++) {

if (arr[i] == otherAddend) {

return new int[] {i, j};

}

}

} else { seen.add(arr[j]);

} } return new int[] {-1, -1};

}

Q3: countFives (2 points)

Write countFives, which takes in an integer and returns the number of times 5 appears as a digit within the number. Examples:

countFives(123467890) // should output 0 countFives(555555) // should output 6 countFives(15354) // should output 2

In order to receive full credit for this problem, you must use recursion. I.e. using =, for, while, etc. is prohibited.

Hint: recall the % and / operators:

123 % 10 // evaluates to 3

123 / 10 // evaluates to 12

Q4: pickTrees (3 points)

You build homes out of wood and you need material from a nearby forest. However, you want to avoid deforestation, so you decide for each tree you cut down, you’ll leave its neighbors alone, giving the forest time to recover. However, you still need as much wood as possible, so you have to be careful about which trees you pick to cut down.

Write pickTrees, which takes in an array of N trees arr where arr[i] represents how much wood you can harvest by cutting down tree i. It should return the max amount of wood you can harvest while following the rule of skipping neighbors:

// Pick tree 0, tree 2, and tree 4 =&gt; 1 + 3 + 5 = 9 wood total int testResult5 = pickTrees(new int[] {1, 2, 3, 4, 5}); System.out.println(testResult5); // should output 9

// Pick tree 1 and tree 3 =&gt; 3 + 3 = 6 wood total int testResult6 = pickTrees(new int[] {1, 3, 4, 3}); System.out.println(testResult6); // should output 6

// Pick tree 0 and tree 3 =&gt; 5 + 9 = 14 wood total int testResult7 = pickTrees(new int[] {5, 1, 4, 9}); System.out.println(testResult7); // should output 14

In order to receive full credit for this problem, you must use recursion. I.e. using =, for, while, etc. is prohibited.
