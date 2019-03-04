# DPR-QUIZ-ALGOS
Algorithm Quiz 1
 
<h4>Please answer the following questions by forking this project. Respond within the README file by editing it. Then submit your Github URL on Canvas</h4>
<ol>
 <li>What does sheevpalpatine.java do? You can copy the code from above and use a browser ide here... https://www.compilejava.net/</li>
 
 As an end result the code presents the response "false". The program starts by creating a word string of "reliefpfpfeiller". The word array is then parsed to a character array that is designed to print true or false if the word presented is a palindrome. Does the word match both left to right and left to right? Simply dividing by 2 to determine even will not present true as a palindrome.  If the second "l" is removed from the latter part of "reiefpfeiller" (Making the word 15 or odd characters) the response will be true.The program is also not functional for supplied words of three characters or less.
 
  <li>Submit a binary search example by adding a file to this project after forking it. Be sure to explain how the example functions using comments or in this README.</li>
  
The file (binarysearch.java attached) researched for this portion reviews a recursive binary search. It maintains the same range as parameters to the function. The very first step is a test of a final condition to stop the recursion.  When a rercusive call finally returns a value, in general it doesn't return the value directly to the call inside the main function. The final call returns a value to the previous call until finally it is returned into main.
  
  
  <li>Is a selection sort or a bubble sort faster?</li>
 </ol>

 Selection sort is faster than bubble sort. Bubble sort is useful though when a given array is "almost sorted" as it can make that determination in the first iteration.
