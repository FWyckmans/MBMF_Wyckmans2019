# MBMF_Wyckmans2019
This folder contains data from the study "Reduced model-based decision-making in gambling disorder" published in 2019 in Scientific Reports by Wyckmans F., Otto R., Sebold M., Daw N., Bechara A., Saeremans M., Kornreich C., Chatard A., Jaafari N. & Noël X..     
https://www.nature.com/articles/s41598-019-56161-z  

This folder includes:  
- The "choice_probs.dat" file contains the probabilities to maintain a choice after a rewarded trial with common transition (second column), after a rewarded trial with a rare transition (third column), an unrewarded trial with common transition (fourth column), and after an unrewarded trial with a rare transition (fifth column).  
- The "choice_regress.dat" file contains data used in the logistic regressions. Please only account for the first column (subj number) and the last five columns (respectively trial number, block number, mn (previous trial rewarded or not), common (previous trial with common or rare transition), and stay (same first step choice or not)). The other columns are dummy variables from another script and do not relate to our participants.  
- "DMFinal.sav" is an SPSS file with clinical measures and MB/MF values computed as Sebold et al. (2014).  
- "dRT1.sav" contains the reaction times after a rewarded or non rewarded trials.  
- The folder "Individual data" contains all the behavioral data of each participant:


Individual file structure:
- The 1st column is the subject number.  
- The 2nd column is not used.  
- The 3rd column is the trial number.  
- The 4th column is the step number (1 or 2). Depending on this column, following columns are different:  
  - Step_1_no_load:  
    - The 5th and 6th columns are the choices offered during the first step.  
    - The 7th column is the choice made. The choice 1 leads to state1 (70% probability), the choice 2 leads to state2 (70%).  
    - The 8th column is the reaction time (ms).  
  - Step_2_no_load:  
    - The 5th and 6th columns are the choices offered during the step (3 and 4 for state1; 5 and 6 for state2).  
    - The 7th and 8th columns are the probability of reward associated with each choice.  
    - The 9th column is the choice made.  
    - The 10th column is the reaction time (ms).  
    - The 11th column is the outcome (1 = rewarded).
  

For more information, please contact Florent Wyckmans (fwyckmans@gmail.com).
