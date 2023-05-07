Download Link: https://assignmentchef.com/product/solved-jac444-workshop-1
<br>
<strong>Description: </strong>

The first Assignment lets you practice basic java coding techniques, creating classes, methods and using arrays.




<strong>Task 1:  </strong>

Design a class named MaxLocation for locating a maximal value and its location in a twodimensional array. The class must contain three data fields

<ul>

 <li>Row (used to store the row indices of a two-dimensional array)</li>

 <li>Column (used to store the column indices of a two-dimensional array)</li>

 <li>maxValue (used to store the maximum value in the two-dimensional array)</li>

</ul>




Choose appropriate datatypes for all the data fields.

Write a method that returns the location of the largest element in a two-dimensional array. The return value should be an instance of MaxLocation class.




Your program that prompts the user to enter a two-dimensional array and displays the location of the largest element in the array.




Here is a sample run:




<sub>                                                  </sub>Enter the number of rows and columns in the array: 3 4

<sub>            </sub>

Enter the array:




23.5   35   2   10

<sup>                                                  </sup>4.5   3   45   3.5

<sup>                                                  </sup>35   44   5.5   9.6

<sup>                                                 </sup>The location of the largest element is 45 at (1, 2)







Students can change the output look as required to make it better in more understandable way.



















<strong>Task 2: </strong>

This task is required to create Craps, which is a popular dice game played in casinos. You are supposed to write a program to play a variation of the game, as follows:

<ul>

 <li>Roll two dice. (Each roll should produce two random numbers between 1 to 6)</li>

 <li>Each die has six faces representing values 1, 2, …, and 6, respectively.</li>

 <li>Check the sum of the two dice. If the sum is 2, 3, or 12 (your program should display <em>craps</em>), you lose the game.</li>

 <li>If the sum of the two dice is 7 or 11 (your program should display <em>naturals</em>), you win the game.</li>

 <li>If the sum of two dice is any value (i.e., 4, 5, 6, 8, 9, or 10), your program should establish a point in the game (meaning store that sum). Continue to roll the dice until the sum is either a 7 or the same point value which was established. If rolled sum is 7, you lose the game. Otherwise, if the rolled sum is equal to established point you win.</li>

</ul>




Your program acts as a single player.




You rolled 5 + 6 = 11

Congratulations, You win




You rolled 1 + 2 = 3

Craps, Better Luck Next Time, You lose




<sub>                                         </sub>You rolled 4 + 4 = 8

<sub>                                         </sub>Point is (established) set to 8

<sub>                                         </sub>You rolled 5 + 1 = 6

You rolled 1 + 1 = 2




You rolled 6 + 2 = 8

<sup>                                         </sup>Congratulations, You Win




<sup>                                         </sup>You rolled 5 + 1 = 6

Point is (established) set to 6

You rolled 2 + 5 = 7

Craps, Better Luck Next Time, You Lose






















<em>Continue to the next page… </em>













Workshop Header




/**********************************************

<strong>Workshop #  </strong>

<strong>Course:</strong><em>&lt;subject type&gt; – Semester </em>

<strong>Last Name:</strong><em>&lt;student last name&gt; </em>

<strong>First Name:</strong><em>&lt;student first name&gt; </em>

<strong>ID:</strong><em>&lt;student ID&gt; </em>

<strong>Section:</strong><em>&lt;section name&gt; </em>

<em>This assignment represents my own work in accordance with Seneca Academic Policy. </em>

<em>Signature </em>

<strong>Date:</strong><em>&lt;submission date&gt; </em>

**********************************************/




<strong> </strong>

Code Submission Criteria:

Please note that you should have:

<ul>

 <li>Appropriate indentation.</li>

 <li>Proper file structure</li>

 <li>Follow java naming convention</li>

 <li>Document all the classes properly</li>

 <li>Do Not have any debug/ useless code and/ or files in the assignment</li>

</ul>




Deliverables and Important Notes:




<strong>All these deliverables are suppose to be uploaded on the blackboard once done. </strong>

<strong> </strong>

<ul>

 <li>You are supposed to create video/ record voice/ detailed document of your running solution. <strong>(50%)</strong>  o Screen Video captured file should state your last name and id, like</li>

</ul>

Ali_123456.mp4 (or whatever the extension of the file is) o Record voice clip should also include a separate word file with the screen shots of your program’s output, state your last name and id, like Ali_123456.mp3 (or whatever the extension of the file is)

o Detailed document should include screen shots of your output, have your name and id on the top of the file and save the file with your last name and id, like Ali_123456.docx (or whatever the extension of the file is)

<ul>

 <li>A word/ text file which will reflect on learning of your concepts in this workshop. Also include the instructions on how to run your code.                                 <strong>(30%)</strong>

  <ul>

   <li>Should state your Full name and Id on the top of the file and save the file with your last name and id, like Ali_123456.txt</li>

  </ul></li>

 <li>Submission of working code.                                                                         <strong>(20%)</strong>

  <ul>

   <li>Make sure your follow the “<strong>Code Submission Criteria”</strong> mentioned above.</li>

   <li>You should zip your whole working project to a file named after your Last Name followed by the first 3 digits of your student ID. For example, zip.</li>

  </ul></li>

 <li>Your marks will be deducted according to what is missing from the above-mentioned submission details.</li>

 <li>Late submissions would result in additional 10% penalties for each day or part of it.</li>

 <li>Remember that you are encouraged to talk to each other, to the instructor, or to anyone else about any of the assignments, but the final solution may not be copied from any source.</li>

</ul>

<strong> </strong>

<h1>Workshop 1</h1>

<strong>Description: </strong>

The first Assignment lets you practice basic java coding techniques, creating classes, methods and using arrays.




<strong>Task 1:  </strong>

Design a class named MaxLocation for locating a maximal value and its location in a twodimensional array. The class must contain three data fields

<ul>

 <li>Row (used to store the row indices of a two-dimensional array)</li>

 <li>Column (used to store the column indices of a two-dimensional array)</li>

 <li>maxValue (used to store the maximum value in the two-dimensional array)</li>

</ul>




Choose appropriate datatypes for all the data fields.

Write a method that returns the location of the largest element in a two-dimensional array. The return value should be an instance of MaxLocation class.




Your program that prompts the user to enter a two-dimensional array and displays the location of the largest element in the array.




Here is a sample run:




<sub>                                                  </sub>Enter the number of rows and columns in the array: 3 4

<sub>            </sub>

Enter the array:




23.5   35   2   10

<sup>                                                  </sup>4.5   3   45   3.5

<sup>                                                  </sup>35   44   5.5   9.6

<sup>                                                 </sup>The location of the largest element is 45 at (1, 2)







Students can change the output look as required to make it better in more understandable way.



















<strong>Task 2: </strong>

This task is required to create Craps, which is a popular dice game played in casinos. You are supposed to write a program to play a variation of the game, as follows:

<ul>

 <li>Roll two dice. (Each roll should produce two random numbers between 1 to 6)</li>

 <li>Each die has six faces representing values 1, 2, …, and 6, respectively.</li>

 <li>Check the sum of the two dice. If the sum is 2, 3, or 12 (your program should display <em>craps</em>), you lose the game.</li>

 <li>If the sum of the two dice is 7 or 11 (your program should display <em>naturals</em>), you win the game.</li>

 <li>If the sum of two dice is any value (i.e., 4, 5, 6, 8, 9, or 10), your program should establish a point in the game (meaning store that sum). Continue to roll the dice until the sum is either a 7 or the same point value which was established. If rolled sum is 7, you lose the game. Otherwise, if the rolled sum is equal to established point you win.</li>

</ul>




Your program acts as a single player.




You rolled 5 + 6 = 11

Congratulations, You win




You rolled 1 + 2 = 3

Craps, Better Luck Next Time, You lose




<sub>                                         </sub>You rolled 4 + 4 = 8

<sub>                                         </sub>Point is (established) set to 8

<sub>                                         </sub>You rolled 5 + 1 = 6

You rolled 1 + 1 = 2




You rolled 6 + 2 = 8

<sup>                                         </sup>Congratulations, You Win




<sup>                                         </sup>You rolled 5 + 1 = 6

Point is (established) set to 6

You rolled 2 + 5 = 7

Craps, Better Luck Next Time, You Lose






















<em>Continue to the next page… </em>













Workshop Header




/**********************************************

<strong>Workshop #  </strong>

<strong>Course:</strong><em>&lt;subject type&gt; – Semester </em>

<strong>Last Name:</strong><em>&lt;student last name&gt; </em>

<strong>First Name:</strong><em>&lt;student first name&gt; </em>

<strong>ID:</strong><em>&lt;student ID&gt; </em>

<strong>Section:</strong><em>&lt;section name&gt; </em>

<em>This assignment represents my own work in accordance with Seneca Academic Policy. </em>

<em>Signature </em>

<strong>Date:</strong><em>&lt;submission date&gt; </em>

**********************************************/




<strong> </strong>

Code Submission Criteria:

Please note that you should have:

<ul>

 <li>Appropriate indentation.</li>

 <li>Proper file structure</li>

 <li>Follow java naming convention</li>

 <li>Document all the classes properly</li>

 <li>Do Not have any debug/ useless code and/ or files in the assignment</li>

</ul>




Deliverables and Important Notes:




<strong>All these deliverables are suppose to be uploaded on the blackboard once done. </strong>

<strong> </strong>

<ul>

 <li>You are supposed to create video/ record voice/ detailed document of your running solution. <strong>(50%)</strong>  o Screen Video captured file should state your last name and id, like</li>

</ul>

Ali_123456.mp4 (or whatever the extension of the file is) o Record voice clip should also include a separate word file with the screen shots of your program’s output, state your last name and id, like Ali_123456.mp3 (or whatever the extension of the file is)

o Detailed document should include screen shots of your output, have your name and id on the top of the file and save the file with your last name and id, like Ali_123456.docx (or whatever the extension of the file is)

<ul>

 <li>A word/ text file which will reflect on learning of your concepts in this workshop. Also include the instructions on how to run your code.                                 <strong>(30%)</strong>

  <ul>

   <li>Should state your Full name and Id on the top of the file and save the file with your last name and id, like Ali_123456.txt</li>

  </ul></li>

 <li>Submission of working code.                                                                         <strong>(20%)</strong>

  <ul>

   <li>Make sure your follow the “<strong>Code Submission Criteria”</strong> mentioned above.</li>

   <li>You should zip your whole working project to a file named after your Last Name followed by the first 3 digits of your student ID. For example, zip.</li>

  </ul></li>

 <li>Your marks will be deducted according to what is missing from the above-mentioned submission details.</li>

 <li>Late submissions would result in additional 10% penalties for each day or part of it.</li>

 <li>Remember that you are encouraged to talk to each other, to the instructor, or to anyone else about any of the assignments, but the final solution may not be copied from any source.</li>

</ul>