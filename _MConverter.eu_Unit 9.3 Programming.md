# Unit 9.3 Programming {#unit-9.3-programming}

Outline of topic:

In this unit, learners will implement algorithms using pseudocode, flowcharts and a text-based programming language. They will explore further programming features in a text-based language to extend their learning from earlier stages. This will include the implementation of count-controlled loops.

Learners will need to make use of pre-existing subroutines to write programs, and will be introduced to string manipulation features, including length, uppercase and lowercase. They will also be introduced to accessing data from arrays.

Learners will also explore the use of compilers and interpreters, including their role in the translation of program code, and the specific features of each.

Recommended prior knowledge:

Learners should have the following prior knowledge:

- Follow a flowchart or pseudocode algorithm that uses conditional statements

- Explain the purpose of a 1-dimensional array

- Know how to develop text-based programs with conditional (selection) statements

- Follow a flowchart or pseudocode algorithm that uses loops

- Understand and use iteration statements, limited to count-controlled loops, presented as either a flowchart or pseudocode

- Know that computers represent data in binary (0, 1)

Language:

- Iteration

- Count-controlled loop

- Subroutine

- Lowercase / Uppercase

- String length

- Array

- Index

- String manipulation

- Translator

- Compiler / Interpreter

- Executable file

<table>
<caption>Suggested teaching activitiesUnder the header row, the rows give suggested teaching activities and resources, along with their associated learning objectives and additional notes.</caption>
<colgroup>
<col style="width: 20%" />
<col style="width: 45%" />
<col style="width: 34%" />
</colgroup>
<thead>
<tr class="header">
<th><strong>Learning objectives</strong></th>
<th><strong>Suggested teaching activities and resources</strong></th>
<th><strong>Additional notes</strong></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><strong>9CT.03</strong> Know how to create algorithms using flowcharts and pseudocode.</td>
<td><p>Introduce this unit by checking learners’ prior knowledge of flowcharts and pseudocode. Ask:</p>
<blockquote>
<p><em>What are the standard flowchart shapes?</em></p>
<p><em>What does an arrow in a flowchart show?</em></p>
<p><strong>Answer:</strong> The direction of flow</p>
<p><em>What rules does pseudocode have?</em></p>
<p><strong>Answer:</strong> There are no set rules, but standard programming symbols should be used instead of English-style sentences</p>
<p><em>When are flowcharts and pseudocode used?</em></p>
<p><strong>Answer:</strong> When designing algorithms and solutions to problems</p>
</blockquote>
<p>Display a flowchart, for example:</p>
<p><img src="media/image1.png" style="width:1.45in;height:3.81229in" alt="Flowchart for a solution that asks for two numbers and then outputs the total of these." /></p>
<p>Ask learners to convert this flowchart into pseudocode. They should compare their response with a partner and discuss any differences. They should consider if these differences are valid or whether there are errors in one, or both, pseudocode algorithms.</p>
<p>Repeat this activity with flowcharts of increasing complexity, for example:</p>
<ul>
<li><p>by introducing multiple operations</p></li>
<li><p>then introducing selection statements.</p></li>
</ul>
<p>Give learners a pseudocode algorithm, for example:</p>
<blockquote>
<p>number1 = input("Enter a number")</p>
<p>number2 = input("Enter a number")</p>
<p>number3 = input("Enter a number")</p>
<p>number4 = input("Enter a number")</p>
<p>if(number1 &gt; number2 and number1 &gt; number2 and number1 &gt; number3 and number1 &gt; number4):</p>
<p>print(number1, " is the largest")</p>
<p>elif(number2 &gt; number3 and number2 &gt; number4):</p>
<p>print(number2, " is the largest")</p>
<p>elif(number3 &gt; number4):</p>
<p>print(number3, " is the largest")</p>
<p>else:</p>
<p>print(number4, " is the largest")</p>
</blockquote>
<p>Ask them to present this pseudocode as a flowchart. They should then compare their responses with a partner and identify any errors, or to determine if they have different, but still accurate, flowcharts.</p>
<p>Give each pair the description of a problem, for example:</p>
<blockquote>
<p><em>Freya wants to work out how much money she will have left at the end of the month. She needs to enter the amount of pocket money she gets each week for 4 weeks. She then needs to enter the 5 products she has bought and how much they cost. The program then needs to output how much money she will have left.</em></p>
</blockquote>
<p>In pairs, ask learners to write a pseudocode algorithm to solve this problem. Each pair should then swap their solution with another, and test whether they work. To support their testing, provide learners with some input data, for example:</p>
<ul>
<li><p>the amount of pocket money received each week</p></li>
<li><p>a list of items and their costs.</p></li>
</ul>
<p>Hold a class discussion to summarise this task. This discussion could be prompted by the following questions:</p>
<blockquote>
<p><em>Did your solutions solve the problems?</em></p>
<p><em>Did you find any errors?</em></p>
<p><em>What were the errors?</em></p>
<p><em>How did you solve them?</em></p>
<p><em>How did you test whether your solution solved the problem?</em></p>
</blockquote>
<p><strong>Resources:</strong></p>
<ul>
<li><p>Set of flowcharts for learners to convert to pseudocode</p></li>
<li><p>Set of pseudocode algorithms for learners to convert to flowcharts</p></li>
<li><p>Set of problems showing algorithms</p></li>
</ul></td>
<td><p>There are a range of possible standard flowchart symbols, the ones listed here are those that match the ones used in the Cambridge International qualifications:</p>
<ul>
<li><p>Rectangle for process</p></li>
<li><p>Rectangle with rounded corners for start and stop</p></li>
<li><p>Parallelogram for input and output</p></li>
<li><p>Diamond for selection.</p></li>
</ul>
<p>The matching pseudocode for this flowchart would be:</p>
<p>num1 = input("Enter a number")</p>
<p>num2 = input("Enter a number")</p>
<p>total = num1 + num2</p>
<p>print("The total is ", total)</p>
<p>A flowchart solution to this algorithm would be:</p>
<p><img src="media/image.png" style="width:3.87342in;height:2.44in" alt="Flowchart to reflect its related pseudocode algorithm" /></p>
<p>A pseudocode solution to this problem would be:</p>
<blockquote>
<p>week = input("Enter the amount of money you get a week")</p>
<p>totalMoney = week * 4</p>
<p>product1 = input("Enter the cost of the first item you bought")</p>
<p>product2 = input("Enter the cost of the second item you bought")</p>
<p>product3 = input("Enter the cost of the third item you bought")</p>
<p>product4 = input("Enter the cost of the fourth item you bought")</p>
<p>totalLeft = totalMoney - product1 - product2 - product3 - product4</p>
<p>print("You will have ", totalLeft, " money left")</p>
</blockquote></td>
</tr>
<tr class="even">
<td><strong>9CT.04</strong> Know how to use predefined sub-routines in flowcharts or pseudocode.</td>
<td><p>Display the term ‘sub-routine’ and ask a learner to explain their understanding of its meaning. Ask other learners to add to the answer until a suitable definition has been achieved. Elicit that:</p>
<ul>
<li><p>a sub-routine is a self-contained program that that can be called from other programs</p></li>
<li><p>sub-routines can be used multiple times in an algorithm and can be used across different algorithms.</p></li>
</ul>
<p>Display a list of instructions for actions that include a subroutine, for example:</p>
<blockquote>
<p>Define: Action 1 = clap 3 times, jump twice, clap 3 times</p>
<p>Action 2 = turn around three times, clap 10 times</p>
</blockquote>
<p>Ask learners to follow these sub-routines, by calling out the following sequence of instruction:</p>
<blockquote>
<p>Stand up</p>
<p>Action 2</p>
<p>Action 1</p>
<p>Sit down</p>
<p>Stand up</p>
<p>Action 1</p>
<p>Action 2</p>
<p>Action 1</p>
<p>Sit down</p>
</blockquote>
<p>Hold a class discussion to determine learners’ understanding of what they have done during this activity. Ask:</p>
<blockquote>
<p><em>What did you do for Action 1?</em></p>
<p><em>How did you know what you had to do?</em></p>
<p><em>Why was it easier to write Action 1 instead of 'clap 3 times, jump twice, clap 3 times' each time?</em></p>
</blockquote>
<p>Remind learners that these are subroutines and help them to recall the definition that was agreed earlier in the activity. Explain that a sub-routine is:</p>
<blockquote>
<p>A set of commands that is given an identifier and can be called from anywhere in an algorithm.</p>
</blockquote>
<p>Elicit that using subroutines means that:</p>
<ul>
<li><p>you do not need to write the same code every time it is used</p></li>
<li><p>each small programme or algorithm only has to be written once but can be used many times within a larger programme or algorithm.</p></li>
</ul>
<p>Display a flowchart subroutine that has already been written, for example a subroutine that converts Celsius to Fahrenheit:</p>
<p><img src="media/image-1.png" style="width:1.33496in;height:3.41813in" alt="Flowchart for a sub-routine to convert Fahrenheit into Celcius " /></p>
<p>Also display a flowchart that makes use of the subroutine, for example:</p>
<p><img src="media/image-2.png" style="width:1.21139in;height:1.69767in" alt="Example flowchart using the &#39;calculate celsius&#39; sub-routine." /></p>
<p>Ask learners to work in pairs to follow the algorithm. Ask one pair to demonstrate the steps they followed, by explaining which instruction they followed.</p>
<p>Give learners another flowchart, for example for a different conversion. Ask them to draw a flowchart that calls this flowchart as a subroutine.</p>
<p>Display a pseudocode subroutine, for example:</p>
<blockquote>
<p>subroutine addition()</p>
<p>firstNumber = input("Enter the first number")</p>
<p>secondNumber = input("Enter the second number")</p>
<p>result = firstNumber + secondNumber</p>
<p>print(firstNumber, " + ", secondNumber, " = ", result)</p>
<p>endsubroutine</p>
</blockquote>
<p>Now provide a program that uses this subroutine, for example:</p>
<blockquote>
<p>answer = input("Do you want to add two numbers together?")</p>
<p>if(answer == "yes"):</p>
<p>addition()</p>
<p>else:</p>
<p>print("Program exiting")</p>
</blockquote>
<p>In pairs, ask learners to follow this program by entering different data, for example:</p>
<ul>
<li><p>"yes", 2, 3</p></li>
<li><p>"yes", 1, 19</p></li>
<li><p>"no".</p></li>
</ul>
<p>Provide each pair with pseudocode subroutines for other mathematical operations, for example subtraction and multiplication, etc. Ask them to extend the above pseudocode program by allowing the user to input which mathematical calculation to follow, and then call the appropriate subroutine.</p>
<p>Summarise learner's work by asking</p>
<blockquote>
<p><em>What is a subroutine?</em></p>
<p><strong>Answer:</strong> A section of code with a name that can be called from another program.</p>
<p><em>How do you call a subroutine in a flowchart or pseudocode?</em> <strong>Answer:</strong> Use its identifier.</p>
</blockquote>
<p><strong>Resources:</strong></p>
<ul>
<li><p>Set of instructions to follow including one or more subroutines</p></li>
<li><p>Flowcharts that use subroutines</p></li>
<li><p>Pseudocode that use subroutines</p></li>
<li><p>Algorithms in flowchart or pseudocode that include pre-written subroutines</p></li>
</ul></td>
<td><p>"yes", 2, 3 would give the output: "2 + 3 = 5"</p>
<p>"yes", 1, 19 would give the output: "1 + 19 = 20"</p>
<p>"no" would give the output "Program exiting"</p>
<p>A subroutine for subtraction could be:</p>
<p>subroutine subtraction()</p>
<p>firstNumber = input("Enter the first number")</p>
<p>secondNumber = input("Enter the second number")</p>
<p>result = firstNumber - secondNumber</p>
<p>print(firstNumber, " - ", secondNumber, " = ", result)</p>
<p>endsubroutine</p></td>
</tr>
<tr class="odd">
<td><p><strong>9CT.06</strong> Understand and use iteration statements, limited to count-controlled loops, presented as either flowcharts or pseudocode.</p>
<p><strong>9CT.09</strong> Combine multiple constructs (sequence, selection, count controlled iteration) to write algorithms as flowcharts or pseudocode.</p>
<p><strong>9P.03</strong> Know how to develop text-based programs with count-controlled loops.</p></td>
<td><p>Gather learner's existing knowledge of count-controlled loops by asking the following questions:</p>
<blockquote>
<p><em>What is iteration?</em></p>
<p><strong>Answer:</strong> Code that repeats multiple times.</p>
<p><em>What is special about a count-controlled loop?</em></p>
<p><strong>Answer:</strong> It runs a set number of times.</p>
<p><em>What features do you find in a count-controlled loop?</em></p>
<p><strong>Answer:</strong> A variable, its start value and its end value.</p>
</blockquote>
<p>Provide learners with a problem that will require them to make use of a count-controlled loop, for example to output the numbers 1 to 100. In pairs, ask them to discuss how to solve the problem. One of each pair should draw a flowchart to solve the problem, and the other should write a pseudocode algorithm. The pairs then compare their ideas to see if they both perform the same function.</p>
<p>Introduce learners to the syntax for programming count-controlled loops in a text-based programming language. In Python, this is:</p>
<blockquote>
<p>for <em>variable</em> in range(<em>startvalue</em>, <em>endvalue +1</em>):</p>
<p><em>code</em></p>
</blockquote>
<p>Provide learners with a help sheet which details the format and example programs that use count-controlled loops. Support them to make their own notes so that they can refer to it when programming.</p>
<p>Ask learners to convert their pseudocode or flowchart into a program using a text-based program, using the sample programs on their help sheet for guidance.</p>
<p>Display a problem that requires the use of a count-controlled loop, for example:</p>
<blockquote>
<p><em>a program needs a user to enter the cost of 20 items, and then output the total and the average.</em></p>
</blockquote>
<p>Ask learners to write a solution to the problem in the text-based language.</p>
<p>Hold a class discussion to check learner’s confidence during this task. This discussion could be informed by the following questions:</p>
<blockquote>
<p><em>Did your programs work first time?</em></p>
<p><em>If not, how did you find the error?</em></p>
<p><em>How did you correct that error?</em></p>
</blockquote>
<p><strong>Resources:</strong></p>
<ul>
<li><p>Problems that require the use of count-controlled loops</p></li>
<li><p>Help sheet that provides the syntax for count-controlled loops in text-based language</p></li>
</ul></td>
<td><p>A pseudocode solution, that follows python syntax, would be:</p>
<p>for x in range (1, 101):</p>
<p>print(x)</p>
<p>In this example, ‘101; has been used because in python this would be where the loop stops. Other languages would stop at ‘100’, for example:</p>
<p>for x = 1 to 100</p>
<p>print(x)</p>
<p>next x</p>
<p>A flowchart solution would be:</p>
<p><img src="media/image-3.png" style="width:3.18972in;height:1.80985in" alt="Example flowchart for a loop which ends when a number exceeds 100" /></p></td>
</tr>
<tr class="even">
<td rowspan="3"><strong>9P.04</strong> Know how to access data from an array using a text-based language.</td>
<td><p>Display an array as a table, for example:</p>
<p><img src="media/image-4.png" style="width:3.63954in;height:0.39183in" alt="Example array" /></p>
<p>Ask a series of questions to check learners’ understanding of this array, for example:</p>
<blockquote>
<p><em>What data is in index 0?</em></p>
<p><strong>Answer:</strong> 30</p>
<p><em>What is the result of the data in index 2 + the data in index 3?</em></p>
<p><strong>Answer:</strong> 35</p>
<p><em>What will be output if the pseudocode statement OUTPUT(array[4]) is run?</em></p>
<p><strong>Answer:</strong> 6</p>
</blockquote></td>
<td><p>Most arrays start with index 0, learners will need reminding that the first element is in index 0, the second in index 1, etc.</p>
<p>Python does not have an inbuilt array data structure. Instead it uses lists that have similar functionality and can be used in place of arrays.</p></td>
</tr>
<tr class="odd">
<td><p>Display the syntax for accessing an array in a text-based language and talk through it. Provide learners with a print-out of the syntax or ask them to make their own notes. Learners’ notes should include:</p>
<ul>
<li><p>how to output the value</p></li>
<li><p>how to store it in a variable to perform other functions, for example to add to another number.</p></li>
</ul></td>
<td><p>Python syntax involves the array name, followed by square brackets with the index inside, for example:</p>
<blockquote>
<p>myArray[0]</p>
</blockquote></td>
</tr>
<tr class="even">
<td><p>In pairs, give learners a program that already has an array declared, with values inserted, for example:</p>
<blockquote>
<p>myArray = [1, 4, 5, 3, 15, 64, 27, 54]</p>
</blockquote>
<p>Give the pairs a list of questions that requires them to write code to produce an answer, for example:</p>
<blockquote>
<p>Output the second element in the array.</p>
<p><strong>Solution:</strong> print(myArray[1])</p>
<p>Output the data in index 0 in the array.</p>
<p><strong>Solution:</strong> print(myArray[0])</p>
</blockquote>
<p>Gradually increase the complexity of the questions, for example by requiring a combination of elements. Example questions include:</p>
<ul>
<li><p>Output the value in index 0 added to the value in index 5.</p></li>
</ul>
<blockquote>
<p><strong>Solution:</strong></p>
<p>print(myArray[0] + myArray[5])</p>
<p><strong>or</strong></p>
<p>firstNum = myArray[0]</p>
<p>secondNum = myArray[5]</p>
<p>total = firstNum + secondNum</p>
<p>print(total)</p>
</blockquote>
<ul>
<li><p>Add together all the elements in the array.</p></li>
</ul>
<blockquote>
<p><strong>Solution:</strong></p>
<p>print(myArray[1])</p>
</blockquote>
<p>For an additional challenge, the use of arrays can be combined with a count-controlled loop, for example:</p>
<ul>
<li><p>Use a count-controlled loop to output each of the array items in turn.</p></li>
</ul>
<blockquote>
<p><strong>Solution:</strong></p>
<p>for x in range(0, 8):</p>
<p>print(myArray[x])</p>
</blockquote>
<p>Give each pair a program that makes use of two arrays, for example one with text and one with numbers such as:</p>
<blockquote>
<p>numberArray = [10, 5, 22, 100, 55, 82, 1]</p>
<p>colourArray = ["red", "purple", "blue", "green"]</p>
</blockquote>
<p>Provide a set of questions to write code to produce answers that involve both arrays, for example:</p>
<ul>
<li><p>Output the third element in the number array with the second colour.</p></li>
</ul>
<blockquote>
<p><strong>Solution:</strong></p>
<p>print(numberArray[2], " ", colourArray[1])</p>
</blockquote>
<p>Hold a class discussion to review learners’ understanding of the programming that they have done during this activity. This discussion can include the following questions:</p>
<blockquote>
<p><em>How do you access data in an array (list) in Python?</em></p>
<p><strong>Answer:</strong> The array’s identifier [index]</p>
<p><em>What is the first index in an array?</em></p>
<p><strong>Answer:</strong> 0</p>
<p><em>What types of bracket do you surround the index with?</em> <strong>Answer:</strong> In Python, square brackets are used.</p>
</blockquote>
<p><strong>Resources:</strong></p>
<ul>
<li><p>Array as a table with indexes and data.</p></li>
<li><p>Program with a numeric array, and list of questions for learners to write code</p></li>
<li><p>Program with two arrays (one numeric and one text-based), and a list of tasks that require learners to write code.</p></li>
</ul></td>
<td><p>This would then need further code adding to enable it to do something with the value, for example:</p>
<ul>
<li><p>to output it: print(myArray[0])</p></li>
<li><p>to store it and perform a calculation with it:</p></li>
</ul>
<blockquote>
<p>myVar = myArray[0] + 2</p>
<p>print(myVar)</p>
</blockquote>
<p>Some learners may identify that some languages start at 1. Also rounded brackets are used in some other programming languages.</p></td>
</tr>
<tr class="odd">
<td rowspan="2"><strong>9P.05</strong> Know how to develop text-based programs using string manipulation, including length, upper case, and lower case.</td>
<td><p>Display a set of words stored in variables, for example:</p>
<blockquote>
<p>word1 = "programming"</p>
<p>word2 = "MANIPULATION"</p>
</blockquote>
<p>Discuss the following questions:</p>
<blockquote>
<p><em>How many letters are in word2?</em></p>
<p><em>What would the data in word1 look like if it was all in capitals?</em></p>
</blockquote>
<p>Discuss the need for string manipulation by asking:</p>
<blockquote>
<p><em>Why do you need to change any words entered into a computer?</em></p>
<p><strong>Answers could include:</strong></p>
</blockquote>
<ul>
<li><p>to access only certain characters</p></li>
<li><p>to split an address</p></li>
<li><p>to check what has been entered.</p></li>
</ul>
<blockquote>
<p><em>Why would you need to find out how many letters were in a word?</em></p>
<p><strong>Answer:</strong> To make sure it was the correct length, to check if a word is entered.</p>
</blockquote></td>
<td rowspan="2"><p>Learners may need prompting, for example with scenarios such as entering a password to help them identify when these may be needed.</p>
<p>In Python these would be:</p>
<blockquote>
<p>len(<em>string</em>)</p>
<p>upper(<em>string</em>)</p>
<p>lower(<em>string</em>)</p>
</blockquote></td>
</tr>
<tr class="even">
<td><p>Display the text-based programming language code for:</p>
<ul>
<li><p>finding the length of a string</p></li>
<li><p>converting a string to upper case</p></li>
<li><p>converting a string to lower case.</p></li>
</ul>
<p>Either give learners a handout that explains the syntax or ask them to make notes.</p>
<p>Share a text-based program that has multiple strings stored in variables, for example:</p>
<blockquote>
<p>word1 = "PROGRAMMING"</p>
<p>word2 = "MaNiPuLaTiOn"</p>
<p>word3 = "eNCRYPTION"</p>
<p>word4 = "network"</p>
</blockquote>
<p>Give learners a set of tasks to add to the program, for example:</p>
<ul>
<li><p>Output the length of the string in word1</p></li>
</ul>
<blockquote>
<p><strong>Solution:</strong> print(len(word1))</p>
</blockquote>
<ul>
<li><p>Convert word2 to lowercase and store it back in the variable word2</p></li>
</ul>
<blockquote>
<p><strong>Solution:</strong> word2 = lower(word2)</p>
</blockquote>
<ul>
<li><p>Store the length of word3 in a variable</p></li>
</ul>
<blockquote>
<p><strong>Solution:</strong> length = len(word3)</p>
</blockquote>
<ul>
<li><p>Convert word3 to uppercase and output the result</p></li>
</ul>
<blockquote>
<p><strong>Solution:</strong> print(upper(word3))</p>
</blockquote>
<ul>
<li><p>Find and output the longest word</p></li>
</ul>
<blockquote>
<p><strong>Solution:</strong></p>
<p>length1 = len(word1)</p>
<p>length2 = len(word2)</p>
<p>length3 = len(word3)</p>
<p>length4 = len(word4)</p>
<p>if(length1 &gt; length2 and length1 &gt; length3 and length1 &lt; length4):</p>
<p>print(word1)</p>
<p>elif(length2 &gt; length3 and length2 &gt; length4):</p>
<p>print(word2)</p>
<p>elif(length3 &gt; length4):</p>
<p>print(word3)</p>
<p>else:</p>
<p>print(word4)</p>
</blockquote>
<p>Give examples that combine strings with an array, for example:</p>
<blockquote>
<p>wordArray = ["house", "car", "balloon", "greenhouse"]</p>
</blockquote>
<p>Ask learners to output the length of each word in the array. The solution is:</p>
<blockquote>
<p>for x in range(0, 4):</p>
<p>print(len(wordArray[x]))</p>
</blockquote>
<p>Check learners’ understanding by holding a class discussion to consider the following questions:</p>
<blockquote>
<p><em>What does the function ‘length’ do?</em></p>
<p><strong>Answer:</strong> It returns the length of the string.</p>
<p><em>What does the function ‘lower’ do?</em></p>
<p><strong>Answer:</strong> It returns the string in lower case.</p>
<p><em>What does the function ‘upper’ do?</em></p>
<p><strong>Answer:</strong> It returns the string in upper case.</p>
<p><em>What would you do to find the length of a string?</em></p>
<p><strong>Answer:</strong> Use the function len</p>
<p><em>How would you find the shortest word?</em></p>
<p><strong>Answer:</strong> Find the length of each word and then use an if statement to compare them.</p>
<p><em>How would you check if the word a user has entered is long enough?</em></p>
<p><strong>Answer:</strong> Find the length of the word and use an if statement to compare it to the minimum length.</p>
</blockquote>
<p><strong>Resources:</strong></p>
<ul>
<li><p>Print-out of string manipulation syntax</p></li>
<li><p>Programs with strings assigned and list of tasks to complete</p></li>
</ul></td>
</tr>
<tr class="odd">
<td><strong>9CS.04</strong> Understand that there are different types of translator, including the main characteristics of compilers and interpreters.</td>
<td><p>To introduce this activity, place large sheets of paper around the room. Each sheet should contain one of the following questions:</p>
<blockquote>
<p><em>In what language does a computer store data?</em></p>
<p><em>In what language does a computer need instructions, to execute them?</em></p>
<p><em>In what language is a text-based programming language, such as Python?</em></p>
<p><em>What has to happen for a computer to run the program you write?</em></p>
</blockquote>
<p>Ask learners to discuss their answer to each question in pairs and to write their agreed answer on a sticky note and at it to the appropriate sheet of paper.</p>
<p>Hold a class discussion to agree a final answer to each question and to address any misconceptions. The answers are:</p>
<p><em>In what language does a computer store data?</em></p>
<p><strong>Answer:</strong> Binary.</p>
<blockquote>
<p><em>In what language does a computer need instructions, to execute them?</em></p>
<p><strong>Answer:</strong> Binary.</p>
<p><em>In what language is a text-based programming language, such as Python, in?</em></p>
<p><strong>Answer:</strong> English.</p>
<p><em>What has to happen for a computer to run the program you write?</em></p>
<p><strong>Answer:</strong> It has to be converted into binary.</p>
</blockquote>
<p>When discussing the final question, explain that converting a program into binary is the role of the translator.</p>
<p>Demonstrate the actions of an interpreter and a compiler, for example Python IDLE is an interpreter. Run a program that contains a syntax error which runs up to the point where the error occurs in an interpreter. Explain that it will not run with a compiler. Where only one of either a compiler or an interpreter is available for the chosen language, such as when only a suitable interpreter can be found for Python, demonstrate a compiler through another language, for example Visual Studio and VB.NET.</p>
<p>Ask the following questions and support learners to provide the answers from their prior knowledge:</p>
<blockquote>
<p><em>What do you run when you want to install, or run, a program on a computer?</em></p>
<p><strong>Answer:</strong> A single file is usually opened that installs the software.</p>
<p><em>What type of file is this?</em></p>
<p><strong>Answer:</strong> An executable file. Be aware that this will need explaining to learners, for example by drawing attention to the ‘.exe’ at the end of the filename.</p>
<p><em>Can you view the code for a program that you buy?</em> <strong>Answer:</strong> Not usually.</p>
</blockquote>
<p>Explain how a compiler produces an executable file when it is run, and how this means that:</p>
<ul>
<li><p>the program can be run without other people being able to access the code</p></li>
<li><p>you can run the file without having to compile it.</p></li>
</ul>
<p>Also explain that the interpreter does not produce this, it has to be interpreted each time.</p>
<p>In pairs, provide learners with a set of cards, each showing a feature of a compiler or interpreter, for example:</p>
<ul>
<li><p>creates an executable file</p></li>
<li><p>translates high-level language to low-level language</p></li>
<li><p>will not run if there are any syntax errors</p></li>
<li><p>will run until it finds a syntax error, and then stops</p></li>
</ul>
<p>Ask the pairs to group the cards into those that:</p>
<ul>
<li><p>only apply to an interpreter</p></li>
<li><p>only apply to a compiler</p></li>
<li><p>apply to both.</p></li>
</ul>
<p>Review each card and address any misconceptions.</p>
<p>Hold a class discussion to consider the following questions:</p>
<blockquote>
<p><em>What software is used to allow you to run your program code?</em></p>
<p><strong>Answer:</strong> A translator</p>
<p><em>What actions does a translator perform?</em></p>
<p><strong>Answer:</strong> It converts high-level language to low-level language. It also checks for syntax errors</p>
<p><em>What are the two types of translator?</em></p>
<p><strong>Answer:</strong> Compilers and interpreters</p>
<p><em>How does a compiler differ from an interpreter?</em></p>
<p><strong>Answer:</strong> A compiler checks all the code and reports all errors and it creates an executable file. An interpreter translates just one statement of a program into machine code at a time.</p>
</blockquote>
<p><strong>Resources:</strong></p>
<ul>
<li><p>large sheets of paper, each displaying a different question</p></li>
<li><p>sticky notes</p></li>
<li><p>cards containing features of compilers and interpreters</p></li>
</ul></td>
<td><p>Learners do not need to understand how the data is translated, or the use of assembly language as an intermediary.</p>
<p>This is a good place to link to copyright, that the code is protected from anyone stealing or editing it.</p>
<p>Demonstrate this by showing the same program but once when it is interpreted and once when it is compiled. Some school networks will lock down .exe files, therefore permission for this demonstration may need to be sought in advance.</p></td>
</tr>
</tbody>
</table>

Suggested teaching activitiesUnder the header row, the rows give suggested teaching activities and resources, along with their associated learning objectives and additional notes.
