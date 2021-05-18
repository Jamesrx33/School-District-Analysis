# **<p align="center">School District Analysis</p>**

### **<p align="center">A Python-based analytics report designed to determine the effects of removing dishonest grade data from a school district report.</p>**

---
## Overview
This report is will show the effects of removing the 9th grade Math and Reading scores for students at Thomas High School. It is assumed that academic dishonesty was practiced and therefore all of the aforementioned scores have been replaced will NULL values. A new district analysis was run after removing this data and displayed below is a comparison of how our seven primary metrics were affected.

---
## **<p align="center">Results Comparison - [Link to Results Folder](https://github.com/Jamesrx33/School-District-Analysis/tree/main/Results)</p>**
---
* **District Summary**: District math averages and all District passing percentages were reduced
  * Original: 
    > ![Old District Summary](https://github.com/Jamesrx33/School-District-Analysis/blob/main/Results/Old_District_Summary.png?raw=true) 
  * Edited:
    > ![New District Summary](https://github.com/Jamesrx33/School-District-Analysis/blob/main/Results/New_District_Summary.png?raw=true)
* **School Summary**: All grade averages and percentages were reduced for Thomas High School
  * Original: 
    > ![Old School Summary](https://github.com/Jamesrx33/School-District-Analysis/blob/main/Results/Old_Per_School_Summary.png?raw=true) 
  * Edited:
    > ![New School Summary](https://github.com/Jamesrx33/School-District-Analysis/blob/main/Results/New_Per_School_Summary.png?raw=true)
* **Best Schools**: Thomas High School remained the second best overall performing school
  * Original: 
    > ![Old Top Five](https://github.com/Jamesrx33/School-District-Analysis/blob/main/Results/Old_Top_Five.png?raw=true) 
  * Edited:
    > ![New Top Five](https://github.com/Jamesrx33/School-District-Analysis/blob/main/Results/New_Top_five.png?raw=true)
* **Scores by Grade Level**:
  * Original: 
    > ![Old Math Scores](https://github.com/Jamesrx33/School-District-Analysis/blob/main/Results/Old_District_Summary.png?raw=true) 
  * Edited:
    > ![New District Summary](https://github.com/Jamesrx33/School-District-Analysis/blob/main/Results/New_District_Summary.png?raw=true)
* **Scores by School Spending**:
  * Original: 
    > ![Old District Summary](https://github.com/Jamesrx33/School-District-Analysis/blob/main/Results/Old_District_Summary.png?raw=true) 
  * Edited:
    > ![New District Summary](https://github.com/Jamesrx33/School-District-Analysis/blob/main/Results/New_District_Summary.png?raw=true)
* **Scores by School Size**:
  * Original: 
    > ![Old District Summary](https://github.com/Jamesrx33/School-District-Analysis/blob/main/Results/Old_District_Summary.png?raw=true) 
  * Edited:
    > ![New District Summary](https://github.com/Jamesrx33/School-District-Analysis/blob/main/Results/New_District_Summary.png?raw=true)
* **Scores by School Type**:
  * Original: 
    > ![Old District Summary](https://github.com/Jamesrx33/School-District-Analysis/blob/main/Results/Old_District_Summary.png?raw=true) 
  * Edited:
    > ![New District Summary](https://github.com/Jamesrx33/School-District-Analysis/blob/main/Results/New_District_Summary.png?raw=true)



---
## Summary
This Election-Analysis script was able to process and display the results of nearly 370,000 votes in a matter of seconds. Given the following modifications (and assuming the same CSV raw data format), we can apply this script to any election of our choosing:
* Implement an input box where a user can input the directory of the CSV file.
   - **file_to_load** = input("Please enter the directory path to the CSV data file.")
* Add to our conditional statement to account for a Tie
   - **if (vote_percentage == winning_percentage):**
   
         winning_count = candidateVotes
         winning_candidate = "There was a Tie, a recount is recommended."
         winning_percentage = vote_percentage
     **elif (candidateVotes > winning_count) and (vote_percentage > winning_percentage):**
     
         winning_count = candidateVotes
         winning_candidate = candidate_name
         winning_percentage = vote_percentage


---
## Reference Documentation - [Source Code Repository](https://github.com/Jamesrx33/election-analysis), [Download .zip file](https://github.com/Jamesrx33/election-analysis/archive/refs/heads/main.zip)
