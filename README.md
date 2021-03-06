# Candidate-Elimination
C++ implementation of the Candidate Elimination Algorithm

Candidate Elimination was implemented on a dataset of animals with 16 features and 7 classes.

**Report**

The report contains the required general and specific boundaries for each class, along with specifying the classes for which the concept cannot be learnt. 

Results for each class are as follows:

**Class 1:**

Specific Boundary:

? 0 ? 1 ? ? ? ? 1 1 0 ? ? ? ? ? 

General Boundary:

? ? ? 1 ? ? ? ? ? ? ? ? ? ? ? ?

**Class 2:**

Specific Boundary:

0 1 1 0 ? ? ? 0 1 1 0 0 2 1 ? ? 

General Boundary:

? 1 ? ? ? ? ? ? ? ? ? ? ? ? ? ? 

0 ? ? ? ? ? ? ? ? ? ? ? 2 ? ? ?

? ? 1 ? ? ? ? ? ? ? ? ? 2 ? ? ? 

? ? ? 0 ? ? ? ? ? ? ? ? 2 ? ? ? 

? ? ? ? ? ? ? 0 ? ? ? ? 2 ? ? ?


**Class 3:**

Concept cannot be learnt.







**Class 4:**

Specific Boundary:

0 0 1 0 0 1 ? 1 1 0 ? 1 0 1 ? ? 

General Boundary:

? ? 1 ? ? ? ? ? ? ? ? 1 ? ? ? ?

? ? ? 0 ? ? ? ? ? ? ? 1 ? ? ? ? 

? ? ? ? ? ? ? ? ? 0 ? 1 ? ? ? ? 

? ? 1 ? ? ? ? 1 ? 0 ? ? ? ? ? ? 

? ? 1 ? ? ? ? ? 1 0 ? ? ? ? ? ? 

? ? 1 ? ? ? ? ? ? 0 ? ? ? 1 ? ? 

? ? 1 ? ? 1 ? 1 ? ? ? ? 0 ? ? ? 

? ? 1 ? ? 1 ? ? 1 ? ? ? 0 ? ? ? 

? ? 1 ? ? 1 ? ? ? ? ? ? 0 1 ? ?


**Class 5:**

Specific Boundary:

0 0 1 0 0 1 ? 1 1 1 ? 0 4 ? 0 0 

General Boundary:

? 0 ? ? ? 1 ? ? ? 1 ? ? ? ? ? 0 

? ? ? ? 0 1 ? ? ? 1 ? ? ? ? ? 0 

? ? ? ? ? 1 ? 1 ? 1 ? ? ? ? ? 0 

? 0 ? 0 ? 1 ? ? ? 1 ? ? ? ? ? ? 

? ? ? ? ? 1 ? 1 ? ? ? ? 4 ? ? 0 

? ? ? ? ? 1 ? ? 1 ? ? ? 4 ? ? 0 

? ? ? ? ? 1 ? ? ? 1 ? ? 4 ? ? 0 

0 0 ? ? ? 1 ? ? ? 1 ? 0 ? ? ? ? 

? ? 1 ? ? 1 ? 1 ? 1 ? ? ? ? ? ? 

? ? 1 ? ? 1 ? 1 ? ? ? 0 ? ? ? ? 

? ? ? 0 ? 1 ? 1 ? 1 ? ? ? ? ? ? 

0 0 1 ? ? 1 ? ? ? 1 ? ? ? ? ? ? 

? 0 1 ? ? 1 ? ? 1 ? ? 0 ? ? ? 0 

? ? 1 ? 0 1 ? ? 1 ? ? 0 ? ? ? 0 

0 ? ? ? ? 1 ? 1 ? 1 ? 0 ? ? ? ? 

0 0 1 ? ? 1 ? ? 1 ? ? 0 ? ? ? ? 

? 0 1 0 ? 1 ? ? 1 ? ? 0 ? ? ? ? 

0 ? ? ? ? 1 ? ? 1 ? ? ? 4 ? ? ? 

0 ? ? ? ? 1 ? ? ? 1 ? ? 4 ? ? ? 

? ? ? 0 ? 1 ? ? 1 ? ? ? 4 ? ? ? 

? ? ? 0 ? 1 ? ? ? 1 ? ? 4 ? ? ? 

0 ? ? ? ? 1 ? 1 ? ? ? ? 4 ? ? ? 

? ? 1 ? ? 1 ? 1 ? ? ? ? 4 ? ? ? 

? ? ? 0 ? 1 ? 1 ? ? ? ? 4 ? ? ?


**Class 6:**

Specific Boundary:

? 0 1 0 ? 0 ? 0 0 1 ? 0 6 0 ? 0 

General Boundary:

? ? ? ? ? 0 ? ? ? ? ? ? 6 ? ? ? 

? ? ? ? ? ? ? ? ? 1 ? ? 6 ? ? ?


**Class 7:**

Concept cannot be learnt.









