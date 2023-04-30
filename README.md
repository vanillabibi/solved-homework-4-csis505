Download Link: https://assignmentchef.com/product/solved-homework-4-csis505
<br>
<strong>Overview</strong>

In this module/week’s homework assignment, you will complete 2 exercises that will allow you to practice your skill at recursion and your understanding of the searching and sorting algorithms that you learned about in the Reading &amp; Study materials for this module/week.

<strong> </strong>

<strong>Instructions</strong>

<ol>

 <li>Refer to the Homework Grading Rubric before you begin this assignment.</li>

 <li>Complete the detailed instructions for each exercise included in the sections below. For each exercise, begin with a new Java project.</li>

 <li>As you write your code, provide all pertinent documentation in the form of JavaDoc comments for all classes and methods.

  <ol>

   <li>All class-level comments must include a description of the class along with your name and links to any outside resources you used (other than the textbook) while writing your code.</li>

   <li>Each method must also have a comment that indicates the purpose of the method and, if applicable, the purpose of all parameters and return value.</li>

   <li>Additional in-line comments must be used to explain complex algorithms or unique solutions to the problem.</li>

  </ol></li>

</ol>

<ol>

 <li>Print, sign, and scan (or take a photo of) the Pledge of Academic Integrity.</li>

</ol>

<ol start="5">

 <li>After you have completed the exercises for this assignment, submit the following via the Blackboard submission link: a digital copy of your signed pledge sheet, a compressed folder containing your code, and any additional written requirements specified below. <strong>Failure to submit a signed pledge of academic integrity for this assignment will result in an automatic grade of zero (0) for this assignment</strong>.</li>

</ol>

<strong> </strong>

<strong>Exercise 1</strong>

<ol>

 <li>Extend the code in Figure 19.3 on pp. 809–811 in the textbook to use a recursive approach to the binary search algorithm. To do this, add a method called that receives the search key, starting index, and ending index as arguments. If the search key is found, return its index in the array, but if the search key is not found, return -1. Add code to the main method to demonstrate that your method works. Ensure that the name of your method includes your last name (e.g., John Doe might use a method name like this: recursiveSearchDoe).</li>

 <li>Take a screenshot of your output, showing the current time and date on your screenshot. Copy your screenshot into a new Word document under an “Exercise 1” heading.</li>

</ol>

<strong></strong>

<strong> </strong>

<strong>Exercise 2</strong>

<ol>

 <li>Create an Evaluator class that will evaluate the sorting algorithms you learned about in this chapter.</li>

</ol>

<ol>

 <li style="list-style-type: none;">

  <ol>

   <li>Create 1 method for each of the sorting algorithms below. Each method must accept 1 int[]as a parameter. Ensure that the name of your method includes your last name (e.g., John Doe might use a method name like this: selectionSortDoe).</li>

  </ol></li>

</ol>

<ol>

 <li style="list-style-type: none;">

  <ol>

   <li style="list-style-type: none;">

    <ol>

     <li>Selection sort</li>

     <li>Insertion sort</li>

     <li>Merge sort</li>

    </ol></li>

   <li>Implement the code for each of the sort methods above by referring to Figures 19.4 (pp. 814–815), 19.5 (pp. 817–819), and 19.6 (pp. 820–822) in the textbook.</li>

   <li>Exclude any portions of the textbook code that print anything to the output window. The goal here is to evaluate the efficiency of the sort algorithms, not how quickly they can print things to the console.</li>

   <li>Add 3 further methods to the Evaluator class that perform the following tasks:</li>

  </ol></li>

</ol>

<ol>

 <li style="list-style-type: none;">

  <ol>

   <li style="list-style-type: none;">

    <ol>

     <li>Returns an array with 100,000 int values in sequential order, starting with 1 and ending with 100,000.</li>

     <li>Returns an array with 100,000 random int values.</li>

     <li>Returns an array with 100,000 int values in descending sequential order, starting with 100,000 and ending with 1.</li>

    </ol></li>

  </ol></li>

 <li>In the main method:</li>

</ol>

<ol>

 <li style="list-style-type: none;">

  <ol>

   <li>Use the Evaluator class to evaluate each sorting algorithm with each of the 3 arrays (best, average, and worst case) for a total of 9 distinct tests.</li>

  </ol></li>

</ol>

<ol>

 <li style="list-style-type: none;">

  <ol>

   <li style="list-style-type: none;">

    <ol>

     <li>Store the result of System.nanoTime() before and after each call to the sorting method, and calculate the time in nano-seconds it takes to complete each test (i.e., subtract the time taken before the test from the time taken after the test).</li>

     <li>Generate new arrays prior to each test, but do not include the generation of the arrays in the evaluation of sort time.</li>

    </ol></li>

   <li>Output a table showing the best, average, and worst case times for each of the sorting algorithms.</li>

  </ol></li>

 <li>Take a screenshot of your output table and paste it into the Word document you created for the first exercise, but place the screen shot under a header for “Exercise 2.” Following the screenshot in the same document, write a brief paragraph (100–200 words) on your findings that comments on whether your observed values are consistent with the Big O notation for each sorting algorithm that the textbook provides (see Figure 19.7 on p. 825). If your results differ substantially from the book, discuss why you believe your results were different. Keep in mind that the notations in Figure 19.7 are only for worst-case scenarios.</li>

 <li>Adjust your array sizes to hold only 1,000 elements and run the 9 tests again. Take another screen shot of your output table and append to the document you created above. Add to the document a brief paragraph (100–200 words) commenting on whether your newly observed values are consistent with the Big O notation that the book provides. If your results differ substantially from the book, discuss why you believe your results were different.</li>

</ol>





