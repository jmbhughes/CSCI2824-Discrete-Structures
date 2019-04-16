# CSCI 2824: Discrete Structures, Summer 2019


### Course Information 
* **Section 300**: MTWH 12:45pm-2:00pm in ECES 112 wtih Andrew Altomare
* **Section 310**: MTWH 2:30pm-3:45pm in ECES 112 with J. Marcus Hughes (this section)


* **Prerequisites**: 
Requires prerequisite courses of (CSCI 1200 or CSCI 1300 or CSCI 1310 or CSCI 1320 or CSCI 2275 or ECEN 1030 or ECEN 1310) and (APPM 1345 or APPM 1350 or MATH 1300 or MATH 1310) (all minimum grade C-).

* **Office Hours**: 
Will be scheduled after evaluating class availability. *I am always available for appointment though!*

### Course philosophy

I am most interested in you learning the material rather than getting a good grade or completing a degree requirement. This material is foundational in computer science and many other fields; you will benefit from thoroughly understanding it. I also find it beautiful and elegant and hope to impart that appreciation to you. I will strive to be accomodating and insightful to maximize your learning this summer. I will emphasize a [growth mindset](https://hbr.org/2016/01/what-having-a-growth-mindset-actually-means) rather than a fixed mindset in every aspect of the course, including in my teaching. If a teaching style is not working for you or a concept is unclear, please tell me. Mistakes are embraced instead of judged; they are how we learn.

### Why Discrete Structures? 

The course covers fundamental ideas from discrete mathematics, especially for computer science students. It focuses on topics that will be foundational for future courses including algorithms, artificial intelligence, programming languages, automata theory, computer systems, cryptography, networks, computer/network security, databases, and compilers.

_Computer Science_ is all about solving interesting problems efficiently and cheaply, using computers! Here are some real problems that keep many computer scientists awake at night:

* Route a packet reliably from one server to another on the internet (faster than [existing protocols](http://en.wikipedia.org/wiki/Routing)? even when routers can fail on us?)
* Search for web pages (better than [Google](http://www.google.com), [Bing](http://www.bing.com) or your favorite search engine??)
* Find the biggest [clique](http://en.wikipedia.org/wiki/Clique) on Facebook. How many people are in this clique? Who are they?
* Understand how to sequence the human genome.
* Find all the prime factors for really large number (> 10^10000).
* Write a program to play _go_ (and play better than the best human champion?).
* Find al anomalies in a data set and explain why they are anomalous (keeps your instructor awake at night!).

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
* **Discrete Probability**: Basic facts, Bayes Rule 
* **Graphs**: Definitions and properties of graphs.
* **Trees**: Definitions and properties of trees.
* **Example Applications**: Artificial Intelligence (automated reasoning, game playing), Graphics (drawing fractals), Cryptography (RSA) and Networks (social network analysis).

### Textbook 

We will use [_Discrete Matheatmics with Applications, 5th ed._](https://www.amazon.com/Discrete-Mathematics-Applications-Susanna-Epp/dp/1337694193/ref=dp_ob_title_bk) by Susanna Epp. Previous iterations of this course have used [_Discrete Mathematics and Its Applications, 7th ed._](https://smile.amazon.com/Discrete-Mathematics-Its-Applications-Seventh/dp/0073383090/ref=sr_1_1?s=books&ie=UTF8&qid=1484628806&sr=1-1&keywords=rosen+discrete+math) by Kenneth H. Rosen. When I took this course I used [_A Discrete Transition to Advanced Mathematics_](https://www.amazon.com/Discrete-Transition-Advanced-Mathematics-Undergraduate/dp/0821847899/ref=sr_1_20?keywords=discrete+mathematics&qid=1554494579&s=gateway&sr=8-20) by Bettina and Thomas Richmond. There are also many open source resources such as [ Discrete Mathematics: An Open Introduction ] (http://discrete.openmathbooks.org/dmoi2/frontmatter.html) by Oscar Levin and [ Applied Discrete Structures ](http://faculty.uml.edu/klevasseur/ads/ads.html) by Al Doerr and Ken Levasseur. In addition, I will make all [course notes](https://github.com/jmbhughes/CSCI2824-Discrete-Structures/tree/master/notes) available before each class. 

All of these books have their strengths and weaknesses. I find that Epp's book has very clear descriptions that will help you throughout the course. I will assign some readings for you to complete before class. If purchasing the book is burden, please let me know, and we will see what we can arrange. You are also welcome to use other texts.


### Course Web Page 

This term we will be using [Piazza](https://piazza.com/colorado/summer2019/csci2824/home) for class discussion. The system is highly catered to getting you help quickly and efficiently from classmates and the instructor. **Rather than emailing me questions, I request that you to post your questions on Piazza**.  If your question is of a private nature, Piazza allows you to send private messages to the instructor.  It is your responsibility to check the web page on a regular basis. Here you will find detailed information such as news, homework assignments and solutions, and instructor office hours. 

### Coursework 

**Weekly Homework**: Homework will be assigned a week before it is due. You are expected to write up your written solutions neatly, with full explanations and justifications. You may discuss problems with your classmates, **but all work must be your own**.  See the **Collaboration Policy** below for more details. 

Homework will consist of proofs and programming assignments. Proofs will help you grow mathematically and allow you to build on the concepts in class. Programming assignments help move the mathematical concepts to an applied setting. Python 3 will be the preferred language for the course programming assignments. Homeworks should be submitted through Gradescope. You are encouraged to use LaTeX when submitting your proofs. Learning how to properly typeset will help you later in your career and looks more professional. To encourage this, I will provide templates and guidance. I will also award a small bonus for using LaTeX. 

Please be mindful of the due dates as unexcused late submissions will not be accepted. If there is some situation that you feel necessitates an extension, please contact me **before** the due date, so we can arrange appropriate modification. Your learning takes priority over deadlines. 

**Quizzes**: We will sometimes have in-class exercises that will count as quiz grades. This will serve to keep you engaged during class as well as serve as an attendance check. In addition, we will have short online quizzes relating to the recent material due every Tuesday and Thursday at 11:59pm. These should not take long and will help you evaluate whether you understand the concepts. I will use them to judge how the course needs to be adjusted.

**Exams**: There will be a two-part midterm half-way through the course and a **cumulative** final exam given during the university scheduled final examination time (TBD).  The midterm will consist of an in-class portion with knowledge check questions and some simpler proofs from in-class and the homeworks. The out-of-class portion will be available for 48 hours and will have some harder proofs and exercises. I do not want you to feel time pressure when trying to create creative proofs. The final will be completely in-class and will assess your overall understanding. Note that due to university regulations, **final exams can only be rescheduled due to official university excused absences**.  Please plan your holiday travel accordingly.  

**You must obtain an average exam score of at least 50% in order to pass the course with a C- or better.**

### Grade Determination 

The overall grades will be based on a cumulative score computed from 

* Weekly homework (50% of the grade)
* Quizzes (10% of the grade)
* Midterm exam (20% of the grade)
* Final exam (20% of the grade)

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

* **Be transparent**: If you find a solution (regardless of if you used it or did not use it) please report it. If you learn of someone else cheating, please tell me privately. Honesty in your course struggles will benefit you.

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



