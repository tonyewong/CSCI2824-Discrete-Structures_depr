# CSCI 2824: Discrete Structures, Spring 2018


### Course Information 

* **Section 001**: MWF 9-9:50 am in GOLD A2B70 with Tony Wong

* **Section 002**: MWF 11-11:50 am in HLMS 252 with Alex Kolla

* **Prerequisites**: 
	* C- or better in Calculus 1 
	* C- or better in CSCI 1200, 1300, or 1320
	* ability (or willingness to learn) to program in Python 3 

* **Office Hours**: 
	* Tony: M/Th/F 10-11 am in ECOT 623, or by appointment
	* Alex: TBA
	* CAs: TBA
	* Graders: TBA  

### Why Discrete Structures? 

The course covers fundamental ideas from discrete mathematics, especially for computer science students. It focuses on topics that will be foundational for future courses including algorithms, artificial intelligence, programming languages, automata theory, computer systems, cryptography, networks, computer/network security, databases, and compilers.

_Computer Science_ is all about solving interesting problems efficiently and cheaply, using computers! Here are some real problems that keep many computer scientists awake at night:

* Route a packet reliably from one server to another on the internet (faster than [existing protocols](http://en.wikipedia.org/wiki/Routing)? even when routers can fail on us?)
* Search for web pages (better than [Google](http://www.google.com), [Bing](http://www.bing.com) or your favorite search engine??)
* Find the biggest [clique](http://en.wikipedia.org/wiki/Clique) on Facebook. How many people are in this clique? Who are they?
* Understand how to sequence the human genome.
* Find all the prime factors for really large number (> 10^10000).
* Write a program to play _go_ (and play better than the best human champion?).
* Write a program to check if a program is “correct” (keeps your instructor awake at night!).

Some of these problems are [really hard](http://en.wikipedia.org/wiki/NP-complete) to solve using a computer. No one knows if there are easy solutions to these problems and it would be nice to see efficient solutions in this century. In this course, we will cover the mathematical foundations that will help us formulate solutions to some of the real problems above. Specifically, we will learn

* How to abstract using mathematical objects such as sets, relations, functions, trees and graphs.
* How to count really well. 
* How to reason like a _pro_: obtain succinct water-tight proofs to guarantee that your solutions are correct, better than a competing solution and all that.
* We will learn these cool mathematical facts, so that in the course of your education as a computer scientist, you will write cool programs to solve interesting problems involving automated reasoning, games, fractals, social networks and the human genome.

### Topics Covered

Roughly, we will cover the following topics (some of them may be skipped depending on the time available).

* **Logic**: Propositional and First Order Logic, Boolean Algebra.
* **Proofs**: Primer on writing proofs, inductions, proof by contradiction.
* **Sets, Relations and Functions**: Basic properties. Paradoxes in naive set theory. Infinite sets. 
* **Recursion**: Recursive functions and recursively defined structures.
* **Combinatorics**: Counting, binomial theorem, counting with recursion.
* **Discrete Probability**: Basic facts, Bayes' Rule 
* **Graphs**: Definitions and properties of graphs.
* **Trees**: Definitions and properties of trees.
* **Example Applications**: Artificial Intelligence (automated reasoning, game playing), Graphics (drawing fractals), Cryptography (RSA) and Networks (social network analysis).

### Textbook 

We will use [_Discrete Mathematics and Its Applications, 7th ed._](https://smile.amazon.com/Discrete-Mathematics-Its-Applications-Seventh/dp/0073383090/ref=sr_1_1?s=books&ie=UTF8&qid=1484628806&sr=1-1&keywords=rosen+discrete+math) by Kenneth H. Rosen.  

We realize the book is pricey, but it's pretty well-written and includes lots of cool computer science applications.  Earlier/international editions are fine, but you'll be responsible for figuring out the section number map between editions for the daily reading. 

### Course Web Page 

[https://piazza.com/colorado/spring2018/csci2824](https://piazza.com/colorado/spring2018/csci2824)

This term we will be using Piazza for class discussion. The system is highly catered to getting you help fast and efficiently from classmates, the grader, and the instructor. **Rather than emailing me questions, I request that you to post your questions on Piazza**.  If your question is of a private nature, Piazza allows you to send me private messages to the instructors.  If you have a question specifically for Tony or Alex, please be sure to address your message to us by name. It is your responsibility to check the web page on a regular basis. Here you will find detailed information such as news, homework assignments and solutions, and instructor office hours. 

### Coursework 

**Weekly Homework**: Homework will be assigned weekly throughout the course.  There will be two types of homework assignments: online homework through Moodle which may include matching, multiple choice, numerical, or programming questions, and written homework which may include by-hand computations, puzzles, and proofs. You are expected to write up your written solutions neatly, with full explanations and justifications. You may discuss problems with your classmates, **but all work must be your own**.  See the **Collaboration Policy** below for more details. **Copying solutions from Chegg or other online "resources" constitutes Academic Dishonesty (that work is NOT your own).** 

Homework is due by **Noon** on the listed due date. **Your two lowest homework scores will be dropped.**   Please be mindful of the due dates as late submissions will not be accepted.  We accept homework at the start of class or underneath our office doors by **Noon**.  We do **NOT** accept emailed homework under any circumstances.

**Exams**: There will be two 90-minute evening midterms during the 6th and 11th weeks of the course and a **cumulative** final exam given during the university-scheduled final examination time.  Note that due to university regulations, **final exams can only be rescheduled due to official university excused absences**.  Please plan your travel accordingly.  

**You must obtain an average exam score of at least 50% in order to pass the course with a C- or better.**

**Course Participation**: Occasionally we will post a short exercise on Moodle to be done between the end of class and the next class meeting. For example, if we post the exercise on Monday after class, it will be due by 8 am on Wednesday morning. These exercises will build on examples and concepts reviewed in class. Thus, if you attend class, they will be relatively short and sweet (5-15 minutes expected). We will announce these exercises **in class** and post them on Moodle. If you miss class, it is your responsibility to check for participation exercise updates.

### Grade Determination 

The overall grades will be based on a cumulative score computed from 

* The weekly homework (30% of the grade)
* The class participation exercises (10% of the grade)
* Two midterm exams (20% of the grade each)
* The final exam (20% of the grade)

Unless adjustments are necessary, letter grades will be assigned using the standard grading scale: 

| Letter | Raw Average |
|--------|-------------|
|     A  |   93-100    |
|     A- |   90-92     |
|     B+ |   87-89     |
|     B  |   83-86     |
|     B- |   80-82     |
|     C+ |   77-79     |
|     C  |   73-76     |
|     C- |   70-72     |
|     D+ |   67-69     |
|     D  |   63-66     |
|     D- |   60-62     |
|     F  |   00-59     |

### Collaboration Policy 

The collaboration policy is simple:

* **Inspiration is free**: you may discuss homework assignments with anyone. You are especially encouraged to discuss solutions with your instructor and your classmates.

* **Plagiarism is forbidden**: the assignments **and code** that you turn in should be written entirely on your own. While writing the assignment you are not allowed to consult any source other than textbooks, your own class notes or the posted lecture slides. Copying/consulting from the solution of another classmate constitutes a violation of the course's collaboration policy and the honor code and will result in an **F** in the course and a trip to the honor council.

* **Do not search for a solution on-line**: You may not actively search for a solution to the problem from the internet. This includes posting to sources like StackExchange, Reddit, Chegg, etc. 

* **When in doubt, ask**: If you have doubts about this policy or would like to discuss specific cases, please ask the instructor.

### Standard Course Policies 

**Honor Code**

All students enrolled in a University of Colorado Boulder course are responsible for knowing and adhering to the [academic integrity policy](http://www.colorado.edu/policies/academic-integrity-policy) of the institution. Violations of the policy may include: plagiarism, cheating, fabrication, lying, bribery, threat, unauthorized access, clicker fraud, resubmission, and aiding academic dishonesty. All incidents of academic misconduct will be reported to the Honor Code Council (honor@colorado.edu; 303-735-2273). Students who are found responsible for violating the academic integrity policy will be subject to nonacademic sanctions from the Honor Code Council as well as academic sanctions from the faculty member. Additional information regarding the academic integrity policy can be found at [www.colorado.edu/honorcode/](http://www.colorado.edu/honorcode/).

**Disability Accommodations**


If you qualify for accommodations because of a disability, please submit your accommodation letter from Disability Services to your faculty member in a timely manner (for exam accommodations provide your letter at least one week prior to the exam) so that your needs can be addressed.  Disability Services determines accommodations based on documented disabilities in the academic environment.  Information on requesting accommodations is located on the [Disability Services website](http://www.colorado.edu/disabilityservices/students).  Contact Disability Services at 303-492-8671 or [dsinfo@colorado.edu](dsinfo@colorado.edu) for further assistance.  If you have a temporary medical condition or injury, see Temporary Medical Conditions under the Students tab on the Disability Services website and discuss your needs with your professor.


**Religious Observances**

Campus policy regarding religious observances requires that faculty make every effort to deal reasonably and fairly with all students who, because of religious obligations, have conflicts with scheduled exams, assignments, or required attendance. If you have an exam or assignment conflict due to a religious observance please notify your instructor in a timely manner. See the [campus policy regarding religious observances](http://www.colorado.edu/policies/observance-religious-holidays-and-absences-classes-andor-exams) for full details.

**Classroom Behavior**

Students and faculty each have responsibility for maintaining an appropriate learning environment. Those who fail to adhere to such behavioral standards may be subject to discipline. Professional courtesy and sensitivity are especially important with respect to individuals and topics dealing with race, color, national origin, sex, pregnancy, age, disability, creed, religion, sexual orientation, gender identity, gender expression, veteran status, political affiliation or political philosophy.  Class rosters are provided to the instructor with the student's legal name. I will gladly honor your request to address you by an alternate name or gender pronoun. Please advise me of this preference early in the semester so that I may make appropriate changes to my records.  For more information, see the policies on [classroom behavior](http://www.colorado.edu/policies/student-classroom-and-course-related-behavior) and the [Student Code of Conduct](http://www.colorado.edu/osccr/).


**Sexual Misconduct, Discrimination, Harassment and/or Related Retaliation**

The University of Colorado Boulder (CU Boulder) is committed to maintaining a positive learning, working, and living environment. CU Boulder will not tolerate acts of sexual misconduct, discrimination, harassment or related retaliation against or by any employee or student. CU's Sexual Misconduct Policy prohibits sexual assault, sexual exploitation, sexual harassment, intimate partner abuse (dating or domestic violence), stalking or related retaliation. CU Boulder's Discrimination and Harassment Policy prohibits discrimination, harassment or related retaliation based on race, color, national origin, sex, pregnancy, age, disability, creed, religion, sexual orientation, gender identity, gender expression, veteran status, political affiliation or political philosophy. Individuals who believe they have been subject to misconduct under either policy should contact the Office of Institutional Equity and Compliance (OIEC) at 303-492-2127. Information about the OIEC, the above referenced policies, and the campus resources available to assist individuals regarding sexual misconduct, discrimination, harassment or related retaliation can be found at the [OIEC website](http://www.colorado.edu/institutionalequity/).



