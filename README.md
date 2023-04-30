Download Link: https://assignmentchef.com/product/solved-cs2310-lab-11-strings
<br>
<strong>Q-1.</strong> Write a program to read a string and count the number of characters and the number of vowels (‘a’, ‘e’, ‘i’, ‘o’, ‘u’) in the string. For the counting of vowels, you should consider both uppercase and lowercase versions of the characters.

<em>Hint:  </em>

<ol>

 <li><em>You may use </em>cin &gt;&gt;<em> to read the string to a char array. </em></li>

 <li><em>You may use the function</em> strlen() in &lt;cstring&gt; <em>to count the number of characters in the string. </em></li>

 <li><em>You may need to define a counter (initialized to 0) and write a for-loop to examine each character in the string (until the null character ‘ ’ is encountered). If the character is vowel, update the count. </em></li>

</ol>

<strong><u>Expected Outputs:</u> </strong>

<table width="0">

 <tbody>

  <tr>

   <td width="301"><strong>Example 1 </strong></td>

   <td width="301"><strong>Example 2 </strong></td>

   <td width="0"></td>

  </tr>

  <tr>

   <td rowspan="2" width="301"><strong>Easter </strong>The number of characters is: 6The number of vowels is: 3</td>

   <td rowspan="2" width="301"><strong>Hello </strong>The number of characters is: 5The number of vowels is: 2</td>

   <td width="0"></td>

  </tr>

  <tr>

   <td width="301"><strong>Example 3 </strong></td>

   <td width="301"><strong>Example 4 </strong></td>

   <td width="0"></td>

  </tr>

  <tr>

   <td rowspan="2" width="301"><strong>AEIOU </strong>The number of characters is: 5The number of vowels is: 5</td>

   <td rowspan="2" width="301"><strong>CityU </strong>The number of characters is: 5The number of vowels is: 2</td>

   <td width="0"></td>

  </tr>

 </tbody>

</table>




<ul>

 <li>Download cpp. Modify it to convert all lowercase letters in a string to uppercase letters and convert all uppercase letters to lowercase letters. The input string may contain multiple words.</li>

</ul>

<em>Hint: You can use </em><em>cin.getline() function in </em><em>&lt;cstring&gt; to read the string to a char array. You may also assume that the maximum size of char array is 50. </em>

<strong><u>Expected Outputs:</u> </strong>

<table width="0">

 <tbody>

  <tr>

   <td width="301"><strong>Example 1 </strong></td>

   <td width="301"><strong>Example 2 </strong></td>

   <td width="0"></td>

  </tr>

  <tr>

   <td rowspan="2" width="301"><strong>HeLLO </strong>hEllo</td>

   <td rowspan="2" width="301"><strong>CityU </strong>cITYu</td>

   <td width="0"></td>

  </tr>

  <tr>

   <td width="301"><strong>Example 3 </strong></td>

   <td width="301"><strong>Example 4 </strong></td>

   <td width="0"></td>

  </tr>

  <tr>

   <td rowspan="2" width="301"><strong>Course 2311 </strong>cOURSE 2311</td>

   <td rowspan="2" width="301"><strong>a Survey </strong>A sURVEY</td>

   <td width="0"></td>

  </tr>

 </tbody>

</table>




<ul>

 <li>Download cpp. The program defines an array called course with six cstrings representing the course titles. Complete the program by sorting course in an ascending alphabetical order.</li>

</ul>

<em>Hints: You can use </em><em>strcmp() for comparison. </em>

<strong><u>Expected Outputs:</u> </strong>

<strong> </strong>

C++ Programming

Data structures

English

Internet

Java Programming

Mathematics




<ul>

 <li>Download cpp. The program defines an array with 10 cstrings representing the students list, and an array with 6 cstrings representing the course list. The program has already <em>randomly</em> assigned each student to register one course. Complete the program so that it can

  <ul>

   <li>count the number of registrations for each course.</li>

   <li>print the course list in descending order according to the number of registrations.</li>

   <li>print the registered students’ names for each course and students’ names should be sorted in ascending alphabetical order.</li>

  </ul></li>

</ul>




<strong>Note:</strong> Your actual output is likely to be different from the expected output if you’re not using Microsoft Visual C++ 2015 (PASS). In case of any inconsistency between your output and PASS output, the PASS output shall prevail.

<strong><u>Expected Outputs:</u> </strong>

<strong> </strong>

<table width="0">

 <tbody>

  <tr>

   <td width="603">Enter the seed for random number generation: <strong><u>234</u> </strong>James registers InternetIverson registers MathematicsWade registers InternetJordan registers Data structuresGeorge registers Java ProgrammingCurry registers Data structuresWestbrook registers C++ ProgrammingDurant registers Java ProgrammingKobe registers Data structuresHarden registers Internet Students’ list:CurryDurantGeorgeHardenIversonJamesJordanKobeWadeWestbrook 3 students register Data structures: Curry Jordan Kobe3 students register Internet: Harden James Wade2 students register Java Programming: Durant George1 student registers Mathematics: Iverson 1 student registers C++ Programming: WestbrookNobody registers English</td>

  </tr>

 </tbody>

</table>


