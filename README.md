# cop3502c-assignment-2-solved
**TO GET THIS SOLUTION VISIT:** [COP3502C Assignment 2 Solved](https://www.ankitcodinghub.com/product/cop-3502c-solved/)


---

📩 **If you need this solution or have special requests:** **Email:** ankitcoding@gmail.com  
📱 **WhatsApp:** +1 419 877 7882  
📄 **Get a quote instantly using this form:** [Ask Homework Questions](https://www.ankitcodinghub.com/services/ask-homework-questions/)

*We deliver fast, professional, and affordable academic help.*

---

<h2>Description</h2>



<div class="kk-star-ratings kksr-auto kksr-align-center kksr-valign-top" data-payload="{&quot;align&quot;:&quot;center&quot;,&quot;id&quot;:&quot;121536&quot;,&quot;slug&quot;:&quot;default&quot;,&quot;valign&quot;:&quot;top&quot;,&quot;ignore&quot;:&quot;&quot;,&quot;reference&quot;:&quot;auto&quot;,&quot;class&quot;:&quot;&quot;,&quot;count&quot;:&quot;1&quot;,&quot;legendonly&quot;:&quot;&quot;,&quot;readonly&quot;:&quot;&quot;,&quot;score&quot;:&quot;5&quot;,&quot;starsonly&quot;:&quot;&quot;,&quot;best&quot;:&quot;5&quot;,&quot;gap&quot;:&quot;4&quot;,&quot;greet&quot;:&quot;Rate this product&quot;,&quot;legend&quot;:&quot;5\/5 - (1 vote)&quot;,&quot;size&quot;:&quot;24&quot;,&quot;title&quot;:&quot;COP3502C Assignment 2 Solved&quot;,&quot;width&quot;:&quot;138&quot;,&quot;_legend&quot;:&quot;{score}\/{best} - ({count} {votes})&quot;,&quot;font_factor&quot;:&quot;1.25&quot;}">

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
Final term Assignment 2

Introduction: For this assignment you have to write a c program that will utilize the Binary Search Tree (BST).

What should you submit?

Write all the code in a single file and upload the .c file.

Please include the following lines in the beginning of your code. By writing this line you also agree that you have written the code:

/* COP 3502C Final term Assignment 2

This program is written by: Your Full Name */

Compliance with Rules: UCF Golden rules apply towards this assignment and submission.

Assignment rules mentioned in the syllabus, are also applied in this submission.

Problem

In this assignment, you have to read a text file (in.txt) that contains a set of words. The first line of the file contains 3 numbers (N, S, D). These numbers represent the sequence of input words in your file.

N: represents the number of words to read to build binary search tree. You have to write a recursive insert code to create and insert these words into the binary search tree. After inserting all the items, you should show the words in Pre order, In order, and Post order. So, you need to create three functions for this purpose.

S: represents the number of the words to search from the tree. These S words are placed after the first N words in the input file.You need to implement a search function that will be able to search these words in your BST.

Additionally, the search words will also be used to look in the binary search tree and count number of words in the tree that come before the search word, alphabetically. You will need to create a recursive function with the following prototype CountBefore(treeNode* root, char searchKey[]), where treeNode is the node structure of your tree.

D: represents the number of words to be deleted from the BST. This list of words are placed after N+S words in the input file. Write a recursive delete function for your task. After deleting all the items, also show the tree in three different orders of traversals.

The figure below shows an example of BST with strings.

Example

Sample Input file in.txt:

9 3 4

judy

mary

bill

alice

tom fred jane

joe

dave

jane jones

judy alice mary judy fred

Sample Output file out.txt:

Pre Order: judy bill alice fred dave jane joe mary tom In Order: alice bill dave fred jane joe judy mary tom Post Order: alice dave joe jane fred bill tom mary judy Search Phase: jane: Found, Items before: 4 jones: Not found, Items before: 0 judy: Found, Items before: 6 Delete Phase: alice: deleted mary: deleted judy: deleted fred: deleted

Pre Order: tom bill jane dave joe //depending on your delete operation it might change In Order: bill dave jane joe tom

Post Order: dave joe jane bill tom //depending on your delete operation it might change

Requirement:

You must use file IO, Binary Search Tree and relevant traversal for your solution.

Your program must compile in EUSTIS.

Rubric:

1) Implementing insertion: 4 (-0.44 for each test case. 9 test cases)

2) In order, postorder, and pre-order: 1.5 (-0.5 for each function)

3) Implementing search: 2 (-0.66 each test case. 3 test cases)

4) Implementing counting count below: 2 (-0.66 each test case 3 test cases)

5) Implementing Delete: 5 (-1.13 for each test case. 4 test cases)

See hint bellow for comparing strings.

Hints: use the strcmp() function of string.h to compare strings. Example strcmp() code bellow.

#include &lt;stdio.h&gt;

#include &lt;string.h&gt;

int main()

{

char str1[] = “abcd”, str2[] = “abce”, str3[] = “bcde”, str4[]=”abCd”, str5[]=”abcd”; int result;

// comparing strings str1 and str2 result = strcmp(str1, str2);

printf(“strcmp(str1, str2) = %d “, result);

result = strcmp(str2, str1);

printf(“strcmp(str2, str1) = %d “, result);

// comparing strings str1 and str3 result = strcmp(str1, str3);

printf(“strcmp(str1, str3) = %d “, result);

// comparing strings str1 and str3 result = strcmp(str3, str1);

printf(“strcmp(str3, str1) = %d “, result);

// comparing strings str1 and str2 result = strcmp(str1, str4);

printf(“strcmp(str1, str4) = %d “, result);

result = strcmp(str4, str1);

printf(“strcmp(str4, str1) = %d “, result);

result = strcmp(str1, str5);

printf(“strcmp(str1, str5) = %d “, result);

return 0;

}

/*output

strcmp(str1, str2) = -1 strcmp(str2, str1) = 1 strcmp(str1, str3) = -1 strcmp(str3, str1) = 1 strcmp(str1, str4) = 1 strcmp(str4, str1) = -1 strcmp(str1, str5) = 0

*/
