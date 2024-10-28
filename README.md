java c
STAT804 Optimization and Operations Research – Assignment 1 (30%)Semester 2, CJLU Cycle 2, 2024 
STAT804 Optimization and Operations Research 
Semester 2, CJLU Cycle 2, 2024 
Assignment 1 (30%)
Due Date: Friday 25 October 2024, 11:59pm
Instructions:  
•  By the due date, you should submit the following four files to Canvas:
– 1 PDF file
*  Your file should contain relevant explanations, mathematical notation, workings and SAS output. Answers which do not include appropriate notation and/or workings, or conversely include too many irrelevant details will be penalised.
* Units of measurement should be included with your answers where relevant (e.g. $, kg).
*  Where you are required to use SAS, a copy of the SAS output should be included within the PDF file (e.g.  as an image).  You do not need to include SAS code within your PDF file.
*  Handwritten submissions are appropriate for some questions. These should be scanned for inclusion in the PDF file.
– 3 SAS files
*  Submit 1 SAS per question.
*  Use comments within your SAS code where appropriate.
*  All SAS files should run on any computer and should not require any additional files.
*  Files which contain unnecessary code or produce unnecessary output will be penalised.
*  SAS code will be assessed based on its accuracy and elegance.
– Do not upload files as a zip.
• Late Assignments:  Failure to submit the assignment on time will result in a penalty in accordance with the DCT late policy (i.e. 5% per day up to a maximum of 5 days).
• Special Consideration:  If extenuating circumstances (e.g. illness) prevent the timely submission of your assignment you can apply for special consideration.  You may also apply for special   consideration if such circumstances result in your submission being incomplete. Applications for special consideration should be submitted via Canvas.
• Originality:  This assignment is an individual piece of work.  You are encouraged to discuss  the assignment with your lecturers and classmates, however, the work you submit must be  your own.  Assignments that show similarities to work submitted by other students will be  investigated for plagiarism and treated very seriously.  Plagiarism software, such as TurnItIn,  maybe used to electronically compare submissions to those of other students and to documents on the internet.
Question: 
1 
2 
3 
Total 
Marks: 
55 
25 
20 
100 
Score: 




1.  StockFood Ltd produces two types of feed for dairy cattle:  FortiSweet10 and ProteinMax.  The feed consists of wheat, barley and soyabean meal. FortiSweet10 contains 50% wheat, 40% barley and 10% soyabean meal. ProteinMax contains 25% wheat, 50% barley and 25% soyabean meal. FortiSweet10 sells for $2.84 per kilogram and ProteinMax sells for $4.45 per kilogram. Each week, StockFood Ltd can purchase up to 200kg of wheat for $0.20 per kg, 300kg of barley for $0.40 per kg and 100kg of soyabean meal for $0.80 per kg.  Demand for each type of feed is unlimited. StockFood Ltd wants to determine the number of kilograms of each feed to produce in order to maximise its profit.
Total for Question 1: 55 marks (a)  Formulate this problem as a linear programming problem by defining the decision variables,    (10 marks)
stating the objective function and stating the constraints.
Note: you can use appropriately defined vectors and matrices in your formulation. (b)  Represent this LP graphically (using pen/paper or software of your choice) and from your      (5 marks)
graph identify an optimal solution.
(c)  Solve this problem by using the Simplex Algorithm (by hand, not using SAS or other software).   (10 marks) At each iteration of the algorithm clearly indicate the entering variable, the leaving variable,
the variables in the basis, and the elementary row operations performed.  After the final
iteration, state the optimal solution and corresponding objective function value. Hint: you should find an optimal solution after 2 iterations.(d)  Is the optimal solution unique? Justify your answer.                                                                               (5 marks)(e)  How much should StockFood Ltd be willing to pay for an additional kilogram of barley? As      (5 marks)
part of your answer, compute the range of feasibility for the relevant constraint.  Interpret your re代 写STAT804 Optimization and Operations Research – Assignment 1C/C++
代做程序编程语言sults in a way that is meaningful for the owner of StockFood Ltd.
Do not resolve the LP. (f)  Suppose that StockFood Ltd can purchase an additional 100kg of wheat for $0.50 per kg?     (5 marks)
Would you recommend that they do so? Justify your answer using appropriate calculations and interpret your results in a way that is meaningful for the owner of StockFood Ltd.
Do not resolve the LP. (g)  Suppose the price of FortiSweet10 increased to $3.  How would this impact the production      (5 marks)
plan of StockFood Ltd? Justify your answer using appropriate calculations and interpret your results in a way that is meaningful for the owner of StockFood Ltd.
Do not resolve the LP. 
(h) Formulate the LP from part (a) in SAS using proc  optmodel. Verify that the solution is the    (10 marks) same as part (c). Use SAS to print the following output:
•  the profit (formatted as a $XXX.XX),
•  the amount of each type of feed produced,
•  a resource usage table showing for each resource: the amount used, the amount available, the percentage used (formatted as a percentage), and the shadow price.
2.  PastureGro imports phosphate for use in its agricultural fertilizers to various ports around New
Zealand and then transports it to its three manufacturing plants. The ports of Auckland, Tauranga
and Christchurch receive shipments of 50, 100 and 50 tonnes per month respectively. The manufacturing plants are located in Napier, Palmerston North and Invercargill. The three plants can produce up
to 80, 90 and 30 tonnes per month respectively.  All phosphate must be transported from the ports to the manufacturing plants to avoid large storage costs. The table below shows the cost of transporting 1 tonne of phosphate between the three ports and the three plants.Total for Question 2: 25 marks 
Plant 
Port 
Napier 
Palmerston North 
Invercargill 
Supply (tonnes) 
Auckland 
$75 
$60 
$69 
50 
Tauranga 
$79 
$73 
$68 
100 
Christchurch 
$85 
$76 
$70 
50 
Demand (tonnes) 
80 
90 
30 
200 (a)  Represent this transportation problem using a directed graph.  Indicate the transportation      (5 marks)
cost on each arc.
(b)  Formulate a linear programming problem which will enable PastureGro to satisfy supply and    (10 marks) demand requirements, and to minimize the total monthly transportation cost.
Note: you can use appropriately defined vectors and matrices in your formulation. 
(c)  Formulate this problem as a linear programming problem in SAS to find an optimal solution.    (10 marks) Write several sentences explaining the transportation plan to the manager at PastureGro.
3.  At the end of their degree, students must undertake a research project. Students rank the projects from a list of available projects.  The academic staff then assign the students to the projects in order to minimize the sum of their preferences.  The cost of assigning a student to his/her first choice is 1, second choice is 2, etc.  For example, if there are m students, and all get their first choice, then the cost of the allocation is m. If two students get their first choice and the remaining m −2 students get their second choice, then the cost of the allocation is 2+2(m −2). Each student can be assigned to at most one project, and each project can be assigned to at most one student. All students must be assigned a project, but it is possible that a project may not be assigned to a student. Note that student B cannot be assigned to project 3 due to requirements specified by the company.
The student preferences and the costs are provided in the table below:
Project 
Student 
1 
2 
3 
4 A B C D 
1 
2 
1 
4 
3 
1 
2 
3 
2 

3 
1 
4 
3 
4 
2 Total for Question 3: 20 marks (a)  Provide a mathematical formulation of this linear programming problem.                                    (10 marks)
Note: you can use appropriately defined vectors and matrices in your formulation. (b)  Formulate this problem as a linear programming problem in SAS and solve it.  Use SAS to    (10 marks)
print a list of the students and the projects to which they have been assigned. Write several sentences to explain the optimal project allocations to the project co-ordinator.







         
加QQ：99515681  WX：codinghelp  Email: 99515681@qq.com
