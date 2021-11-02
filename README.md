### School_District_Analysis

#### 1. OVERVIEW OF THE SCHOOL DISTRICT ANALYSIS:

The purpose of this anlysis is to replace the math and reading scores for Thomas High School with NaNs while the other details remain the same. After the math and reading scores are replaced,  the school district analysis in this module is repeated and a report is created to describe how these changes affected the overall analysis.  

#### 2. OVERVIEW OF THE SCHOOL DISTRICT ANALYSIS:

A) How is the district summary affected?

    > BEFORE REPLACING DATA
      * Average Math Score, Average Reading Score, % Passing Math, % Passing Reading, % Overall Passing
      * 79.0, 81.9, 75, 86, 65
    > AFTER REPLACING DATA
      * Average Math Score, Average Reading Score, % Passing Math, % Passing Reading, % Overall Passing
      * 78.9, 81.9, 74, 85, 64
    > OBSERVATION: Slight decrease in district averages
    
B) How is the school summary affected?

    > BEFORE REPLACING DATA:  Thomas High School's % Overall Passing = 91, ranking second
    > AFTER REPLACING DATA:   % Overall Passing = 65, placing eighth
    > OBSERVATION:            Overall ranking order of Thomas High School slipped from 2ND to 13TH position
    
C) How does replacing the ninth graders’ math and reading scores affect Thomas High School’s performance relative to the other schools?

   The relative ranking of Thomas High School changed from 2ND to 8TH because it's % Overall passing decreased from 91% to 65%.
   
D) How does replacing the ninth-grade scores affect the following:

    Math and reading scores by grade: 
    > Totals for passing math & reading across grades are reduced because 9th grade scores are set to NAN.
    > "%age passing" score is reduced because the total passing value (numerator) is reduced by the removal of 9th grade scores.
    
    Scores by school spending:
    > Thomas HS is in the spending bin range "$630-644"
    > Removing 9th grade scores reduces the "% Passing Math", "% Passing Reading" and "% Overall Passing" scores for spending bin 
      "$630-644" as follows -
        * BEFORE REPLACING DATA: 73, 84, 63
        * AFTER REPLACING DATA: 67, 77, 56
        
    > Scores by school size :
        * Thomas HS is in the "Medium (1000-2000)" size bucket
        * Removing 9th grade scores reduces the "% Passing Math", "% Passing Reading" and "% Overall Passing" scores for size
          bin  "Medium (1000-2000)" as follows:
          * BEFORE REPLACING DATA:94, 97, 91
          * AFTER REPLACING DATA: 88, 91, 85
          
    > Scores by school type :
        * Thomas High School is in the "CHARTER" type 
        * Removing 9th grade scores reduces the "% Passing Math", "% Passing Reading" and "% Overall Passing" scores for type                 "CHARTER" as follows:
          * BEFORE:94, 97, 90
          * AFTER: 90 93 87

3. Summary:
