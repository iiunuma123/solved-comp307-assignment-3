Download Link: https://assignmentchef.com/product/solved-comp307-assignment-3
<br>
<em>Introduction to AI</em>

<strong>Uncertainty and Probability</strong>

<em>20% of Final Mark </em>

<h1>1       Question Description</h1>

<h2>Part 1: Reasoning Under Uncertainty Basics [30 marks]</h2>

This part contains several questions about the basics of reasoning under uncertainty. You need to write your answers to each of these questions in your report, and <strong>Show your working.</strong>

For calculations, you need to show the steps in the form like, to demonstrate that you <em>know how to calculate </em>them.

For proving, you also need to show the steps during the proof.

<h3>Question 1 [10 marks]</h3>

The tables below give the prior distribution <em>P</em>(<em>X</em>), and two conditional distributions <em>P</em>(<em>Y </em>|<em>X</em>) and <em>P</em>(<em>Z</em>|<em>Y </em>). It is also known that <em>Z </em>is independent from <em>X </em>given <em>Y </em>. All the three variables (<em>X</em>, <em>Y </em>, and <em>Z</em>) are binary variables. Compute the table of their joint distribution based on the chain rule.

<table width="196">

 <tbody>

  <tr>

   <td width="48">


    <table width="45">

     <tbody>

      <tr>

       <td width="15"></td>

       <td width="30"></td>

      </tr>

      <tr>

       <td width="15">0</td>

       <td width="30">0.300</td>

      </tr>

      <tr>

       <td width="15">1</td>

       <td width="30">0.700</td>

      </tr>

     </tbody>

    </table></td>

   <td width="147">


    <table width="144">

     <tbody>

      <tr>

       <td width="14"></td>

       <td width="15"></td>

       <td width="41"></td>

       <td rowspan="5" width="6"> </td>

       <td width="14"></td>

       <td width="14"></td>

       <td width="39"></td>

      </tr>

      <tr>

       <td width="14">0</td>

       <td width="15">0</td>

       <td width="41">0.300</td>

       <td width="14">0</td>

       <td width="14">0</td>

       <td width="39">0.600</td>

      </tr>

      <tr>

       <td width="14">1</td>

       <td width="15">0</td>

       <td width="41">0.700</td>

       <td width="14">1</td>

       <td width="14">0</td>

       <td width="39">0.400</td>

      </tr>

      <tr>

       <td width="14">0</td>

       <td width="15">1</td>

       <td width="41">0.800</td>

       <td width="14">0</td>

       <td width="14">1</td>

       <td width="39">0.800</td>

      </tr>

      <tr>

       <td width="14">1</td>

       <td width="15">1</td>

       <td width="41">0.200</td>

       <td width="14">1</td>

       <td width="14">1</td>

       <td width="39">0.200</td>

      </tr>

     </tbody>

    </table></td>

  </tr>

 </tbody>

</table>

<ol>

 <li>Create the full joint probability table of <em>X </em>and <em>Y </em>, i.e. the table containing the following four joint probabilities <em>P</em>(<em>X </em>= 0<em>,Y </em>= 0), <em>P</em>(<em>X </em>= 0<em>,Y </em>= 1), <em>P</em>(<em>X </em>= 1<em>,Y </em>= 0), <em>P</em>(<em>X </em>= 1<em>,Y </em>= 1).</li>

</ol>

Also explain which probability rules you used.

<ol start="2">

 <li>If given <em>P</em>(<em>X </em>= 1<em>,Y </em>= 0<em>,Z </em>= 0) = 0<em>.</em>336, <em>P</em>(<em>X </em>= 0<em>,Y </em>= 1<em>,Z </em>= 0) = 0<em>.</em>168, <em>P</em>(<em>X </em>= 0<em>,Y </em>= 0<em>,Z </em>= 1) = 0<em>.</em>036, and <em>P</em>(<em>X </em>= 0<em>,Y </em>= 1<em>,Z </em>= 1) = 0<em>.</em>042, create the full joint probability table of the three variables <em>X</em>, <em>Y </em>, and <em>Z</em>. Also explain which probability rules you used.</li>

 <li>From the above joint probability table of <em>X</em>, <em>Y </em>, and <em>Z</em>:

  <ul>

   <li>calculate the probability of <em>P</em>(<em>Z </em>= 0) and <em>P</em>(<em>X </em>= 0<em>,Z </em>= 0), (ii) judge whether <em>X </em>and <em>Z </em>are independent to each other and explain why.</li>

  </ul></li>

 <li>From the above joint probability table of <em>X</em>, <em>Y </em>, and <em>Z</em>:

  <ul>

   <li>calculate the probability of <em>P</em>(<em>X </em>= 1<em>,Y </em>= 0|<em>Z </em>= 1), (ii) calculate the probability of <em>P</em>(<em>X </em>= 0|<em>Y </em>= 0<em>,Z </em>= 0).</li>

  </ul></li>

</ol>

<h3>Question 2 [10 marks]</h3>

Consider three Boolean variables <em>A</em>, <em>B</em>, and <em>C</em>, <em>A </em>⊥ <em>B</em>|<em>C</em>, <em>P</em>(<em>B</em>) = 0<em>.</em>7, <em>P</em>(<em>C</em>) = 0<em>.</em>4, <em>P</em>(<em>A</em>|<em>B</em>) = 0<em>.</em>3, <em>P</em>(<em>A</em>|<em>C</em>) = 0<em>.</em>5, and <em>P</em>(<em>B</em>|<em>C</em>) = 0<em>.</em>2, calculate the following probabilities. <strong>Show your working.</strong>

<ul>

 <li><em>P</em>(<em>B,C</em>)</li>

 <li><em>P</em>(¬<em>A</em>|<em>B</em>)</li>

 <li><em>P</em>(<em>A,B</em>|<em>C</em>)</li>

 <li><em>P</em>(<em>A</em>|<em>B,C</em>)</li>

 <li><em>P</em>(<em>A,B,C</em>)</li>

</ul>

<h3>Question 3 [10 marks]</h3>

Dragonfly has a rare species, which always has an extra set of wings. However, common dragonflies can sometimes mutate and get an extra set of wings. A dragonfly either belongs to the common species or the rare species with the extra wings. There are 0.3% dragonflies belonging to the rare species with the extra set of wings. For the common dragonflies, the probability of the extra-wing mutation is 0.1%. Now you see a dragonfly with an extra pair of wings. What is the probability that it belongs to the rare species? <strong>Show your working.</strong>

<h3>Question 4 [for COMP420 ONLY, 10 marks]</h3>

Prove the following statements. <strong>Show your working.</strong>

<ul>

 <li>If <em>P</em>(<em>A</em>|<em>B,C</em>) = <em>P</em>(<em>B</em>|<em>A,C</em>), then <em>P</em>(<em>A</em>|<em>C</em>) = <em>P</em>(<em>B</em>|<em>C</em>)</li>

 <li>If <em>P</em>(<em>A</em>|<em>B,C</em>) = <em>P</em>(<em>A</em>), then <em>P</em>(<em>B,C</em>|<em>A</em>) = <em>P</em>(<em>B,C</em>)</li>

 <li>If <em>P</em>(<em>A,B</em>|<em>C</em>) = <em>P</em>(<em>A</em>|<em>C</em>) ∗ <em>P</em>(<em>B</em>|<em>C</em>), then <em>P</em>(<em>A</em>|<em>B,C</em>) = <em>P</em>(<em>A</em>|<em>C</em>)</li>

</ul>

<h2>Part 2: Naive Bayes Method [25 marks]</h2>

This part is to implement the Naive Bayes algorithm, and evaluate the program on the spam data set to be described below. The program should build a Naive Bayes classifier from the labelled data set and apply it to the unlabelled set.

<h3>Problem Description</h3>

The labelled data set is in the file spamLabelled.dat, which describes 200 emails, labelled as <em>spam </em>or <em>non-spam</em>. Each email is specified by 12 binary attributes, indicating the presence of features such as “Viagra”, “MILLION DOLLARS”, significant amounts of text in CAPS, an invalid reply-to address, and so on. Note that there are 2<sup>12</sup>=4096 possible input patterns, compared to a data set of just 200 examples.

The layout of the data is that each row is an instance of features from one email, and columns correspond to the features, which are binary: the feature is either there or not. The last (rightmost) column is the class: 1 = spam, 0 = non-spam.

The file spamUnlabelled.dat contains 10 new input patterns to be classified.

There’s a good entry in wikipedia (http://en.wikipedia.org/wiki/Naive Bayesian classifier that discusses exactly the domain we’re applying the algorithm to. You are recommended to read this article.

As we discussed during the lectures, zero probabilities are a problem for the Naive Bayes method. For example, if the training data did not include a <em>C </em>= 1 instance with attribute F8 = 1, the simplest version of the algorithm will assume that <em>P</em>(<em>C </em>= 1|<em>F</em>8 = 1) = 0, and never predict <em>C </em>= 1 if <em>F</em>8 = 1. This is generally a bad idea because <em>P</em>(<em>C </em>= 1|<em>F</em>8 = 1) is unlikely to be exactly zero, even if it is very low. The simplest solution is to initialise all the counts to 1, rather than 0, which means every <em>P</em>(<em>C</em>|<em>F</em>) has at least a low probability. As discussed in the lecture, you should divide by the right number when you convert the counts into probabilities.

<h3>Requirements</h3>

Your job is to use the Naive Bayes method to classify the unlabelled instances in the spamUnlabelled.dat file. The method should use the training data in spamLabelled.dat to construct the classifier (Naive Bayes probability tables), and then apply the classifier to the data in spamUnlabelled.dat

<strong>You should implement the Naive Bayes method from scratch (not call it from any machine learning library)</strong>. Your program should take two file names as command line arguments, construct a classifier from the data in the first file, and then apply the classifier to the data in the second file.

You may write the program code in Java, C/C++, or any other programming language.

You should submit the following files electronically and also a report.

<ul>

 <li>(15 marks) Program code for your Naive Bayes Classifier (both the source code and the executable program running on ECS School machines),</li>

 <li>(2 marks) txt containing the output of your program on the unlabelled data set, and</li>

 <li>(8 marks) A report in PDF, text or DOC format. The report should include:

  <ol>

   <li>the probabilities <em>P</em>(<em>F<sub>i</sub></em>|<em>c</em>) for each feature <em>i</em>.</li>

   <li>For each instance in the unlabelled set, given the input vector <em>F</em>, the probability <em>P</em>(<em>S</em>|<em>D</em>), the probability <em>P</em>(<em>S</em>¯|<em>D</em>), and the predicted class of the input vector. Here D is an email represented by <em>F</em>, <em>S </em>refers to class <em>spam </em>and <em>S</em>¯ refers to class <em>non-spam</em>.</li>

   <li>The derivation of the Naive Bayes algorithm assumes that the attributes are conditionallyindependent. Why is this like to be an invalid assumption for the spam data? Discuss the possible effect of two attributes not being independent.</li>

  </ol></li>

</ul>

<h2>Part 3: Bayesian Networks: Questions [30 marks]</h2>

This part contains several questions about Bayesian networks. You will need to write your answers in the report and <strong>show your working</strong>.

Consider the Bayesian network below, where all the variables are boolean.

<strong>Question 1 [5 marks] </strong>Write the factorisation of this Bayesian network.

<strong>Question 2 [5 marks] </strong>Describe under which condition the following pair of nodes will be (conditionally) independent. For example, <em>A and E are conditionally independent given C</em>.

<ul>

 <li>A and B.</li>

 <li>A and D.(iii) B and G.</li>

 <li>D and F.</li>

 <li>C and G.</li>

</ul>

<strong>Question 3 [10 marks] </strong>Draw the Bayesian network if the node ordering is <em>E </em>→ <em>D </em>→ <em>F </em>→ <em>G </em>→

<em>B </em>→ <em>C </em>→ <em>A</em>.

<strong>Question 4 [10 marks] </strong>Suppose <em>P</em>(<em>A</em>) = 0<em>.</em>7, <em>P</em>(<em>B</em>) = 0<em>.</em>2, <em>P</em>(<em>C</em>|<em>A</em>) = 0<em>.</em>6, <em>P</em>(<em>C</em>|¬<em>A</em>) = 0<em>.</em>3, <em>P</em>(<em>D</em>|<em>B,C</em>) = 0<em>.</em>7, <em>P</em>(<em>D</em>|<em>B,</em>¬<em>C</em>) = 0<em>.</em>6, <em>P</em>(<em>D</em>|¬<em>B,C</em>) = 0<em>.</em>5, <em>P</em>(<em>D</em>|¬<em>B,</em>¬<em>C</em>) = 0<em>.</em>2. Calculate the probability <em>P</em>(<em>D</em>).

<h2>Part 4: Building Bayesian Network [30 marks]</h2>

This part is to build a Bayesian Network for the problem described below.

<h3>Problem Description</h3>

Dr. Rachel Nicholson is a Professor, who lives far away from her university. So, she prefer to work at home and she only comes to her office if she has research meetings with her postgraduate students, or teaching lectures for undergraduate students, or she has both meetings and teaching:

<ul>

 <li>The probability for Rachel to have meetings is 70%, the probability of Rachel has lectures is 60%.</li>

 <li>If Rachel has both meetings and lectures, the probability of Rachel comes to her office is 95%.</li>

 <li>If Rachel only has meetings (without lectures), the probability of Rachel comes to her office is 75% because she can Skype with her students.</li>

 <li>If Rachel only has lectures (without meetings), the probability of Rachel comes to her office is 80%.</li>

 <li>If Rachel has neither meetings nor lectures, there is a only 6% chance that she comes to the office.</li>

 <li>When Rachel is in her office, half the time her light is off (when she is trying to hide from others to get work done quickly).</li>

 <li>When she is not in her office, she leaves her light on only 2% of the time since the cleaners come for cleaning.</li>

 <li>When Rachel is in her office, 80% of the time she logged onto the computer.</li>

 <li>Because she sometimes work from home, 20% of the time she is not in her office, she is still logged onto the computer.</li>

</ul>

Note regarding the calculation, you should show your <em>working process </em>of the calculation to demonstrate that you <em>know how to calculate </em>them.

<h3>Requirements</h3>

<ol>

 <li>Construct a Bayesian network to represent the above scenario. (<em>Hint: First decide what your domain variables are; these will be your network nodes. Then decide what the causal relationships are between the domain variables and add directed arcs in the network from cause to effect. Finally, you have to add the prior probabilities for nodes without parents, and the conditional probabilities for nodes that have parents.</em>)</li>

 <li>Calculate how many free parameters in your Bayesian network ?</li>

 <li>What is the joint probability that Rachel has lectures, has no meetings, she is in her officeand logged on her computer but with lights off.</li>

 <li>Calculate the probability that Rachel is in the office.</li>

 <li>If Rachel is in the office, what is the probability that she is logged on, but her light is off.</li>

 <li>Suppose a student checks Rachel’s login status and sees that she is logged on. What effectdoes this have on the student’s belief that Rachel’s light is on ?</li>

</ol>

<h2>Part 5: Bayesian Network: Applications [For COMP420 ONLY, 20 marks]</h2>

Identify a real-world application (<strong>different from the examples given in this assignment and the lectures</strong>) that can be described using Bayesian network. There should be at least 5 random variables in this Bayesian network.

<strong>In your report, you should:</strong>

<ul>

 <li>Clearly define the random variables and their domains.</li>

 <li>Clearly describe their relationships (using plain language).</li>

 <li>Draw the Bayesian network that can reflect the described relationship.</li>

 <li>Write the factorisation of the Bayesian network.</li>

</ul>

<h1>2          Relevant Data Files and Program Files</h1>

The relevant data files, information files about the data sets, and some utility programs files can be found from the following directory:

/vol/comp307/assignment3/

<h1>3      Assessment</h1>

We will endeavour to mark your work and return it to you as soon as possible, hopefully in 2 weeks. The tutor(s) will run a number of helpdesks to provide assistance.

<h1>4       Submission Guidelines</h1>

<h2>4.1      Submission Requirements</h2>

<ol>

 <li>Programs for all individual parts. To avoid confusion, all the individual parts should usedirectories part1/, part2/, … and all pieces of programs should be stored in their corresponding directories. Within each directory, please provide a readme file that specifies how to compile and run your program. A script file called txt should also be provided to show how your program run properly. If you programs cannot run properly, you should provide a buglist file.</li>

 <li>A report document that consist of <strong>the answers of all the individual parts</strong>. The document should mark each part clearly. The document can be written in PDF, text or the DOC format.</li>

 <li>For drawing the diagram such as the Bayesian network, you need to <strong>make the diagram very clear to be marked</strong>. We highly recommend using drawing tools rather than by hand.</li>

</ol>

<h2>4.2      Submission Method</h2>

The programs and the PDF/Text/DOC version of the document should be submitted through web submission system from the COMP307/420 course web site <strong>by the due time</strong>.

<h2>4.3      Late Penalties</h2>

All assignments must be submitted on time unless you have made a prior arrangement with the lecturer or have a valid medical excuse (for minor illnesses it is sufficient to discuss this with the lecturer.) The penalty for assignments that are handed in late without prior arrangement is one grade reduction per day. Assignments that are more than one week late will not be marked.