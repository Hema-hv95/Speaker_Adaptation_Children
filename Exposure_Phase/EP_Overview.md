**Information about the Exposure_Phase directory:**  

Contains all the resources, documents and code pertaining to the exposure phase of the experiment, including:
- Videos of the character Sam posing questions to the participants pertaining to images of the gumball machines, and providing agreements or disagreements with the participants' answers.  
- CSV file used by the code to generate trials.  
- Javascript code for use on the PCIbex farm.  
- Script containing the interactions and responses of the character during the exposure phase, available in the Exposure_Phase directory as a file named "EP_Script".

Elements absent from this directory that are still used in the exposure phase trials include:
- The green button animation and red button animations. 
  - The participant will select one of the buttons to indicate "yes" or "no", respectively. 
  - These video animations can be found in "Buttons" which is available as a separate folder in the main branch.
- The images of the gumball machine.
  - These can be found in "Gumball_Machines" which is available as a separate folder in the main branch.

**Information about the Exposure Phase:**

The experiment to which the exposure phase belongs attempts to evaluate the speaker adaptation abilities of children in the age range of 5 to 8. Here, speaker adaptation describes the linguistic phenomenon in which the listener develops a mental model for the speaker's specific conceptualisation/understanding of a particular linguistic unit. Thus, the exposure phase exposes the participant to the thresholds of the cartoon character Sam for vague quantifiers such as "many" and "few", and test phase tests if these thresholds are recognized by the participant, i.e., whether they have developed a mental model for them. 

Each trial follows the following format:
- An image of a gumball machine containing a particular ratio of blue gumballs to orange gumballs is presented on the screen, along with the cartoon character Sam, and two buttons - one green and one red.
- The participant is informed that the image is visible to both them and the character Sam.
- Sam poses a question: "Do you think many/few/all/none of the gumballs are blue/orange?"
- The participant may click on the green button to answer "yes" and the red button to answer "no".
- At this juncture, Sam may either agree or disagree with the participant's judgement, depending on his pre-programmed intuitions. These intuitions can embody either one of two different conditions:
  - In speaker condition 1, the threshold for the use of many will be lower, i.e., ratios 40 percent and above can be described as many. Accordingly, Sam will be inclined to use few only with ratios below 40 percent.
  - In speaker condition 2, the threshold for the use of many will be higher, i.e., only ratios 60 percent and above can be described as many. Accordingly, Sam will be inclined to use few with ratios below 60 percent.

There are 18 trials in total. Trials using the quantifiers "all" and "none" are accompanied by the ratios 0 or 100, i.e. Trials using the quantifiers "many" and "few" are accompanied by the ratios 20, 40, 60, or 80, and they are interspersed by "all" and "none" trials, which act as attention checks. The counts for the different categories of trials are as follows:
- Ratio 100 ; Quantifier "All" - 1
- Ratio 0 ; Quantifier "None" - 1
- Ratio 20 ; Quantifier "Few" - 1 ; Quantifier "Many" - 1
- Ratio 80 ; Quantifier "Few" - 1 ; Quantifier "Many" - 1
- Ratio 40 ; Quantifier "Few" - 3 ; Quantifier "Many" - 3
- Ratio 60 ; Quantifier "Few" - 3 ; Quantifier "Many" - 3
Here, the ratio refers to the percent of gumballs of one colour with respect to the other colour. 20 percent ratio means 20 percent of the gumballs are blue, if the question targets blue gumballs, or 20 percent are orange, if the question targets orange gumballs. The quantifier refers to quantifier used in the question. Thus, trial using ratio 20 and quantifier "Few" will use the question "Do you think few of the gumballs are blue/orange?" and use a gumball machine containing either 20 percent blue gumballs or 20 percent orange gumballs (depending on the target chosen by the question).

A within-subject design is used in terms of the target colour, i.e., whether the question is addressing the amount of orange gumballs or the amount of blue gumballs. The trials shuffle between orange and blue for each participant. A between-subject design is used in terms of the speaker condition, i.e., whether the character embodies speaker 1 or speaker 2. No participant will be exposed to both conditions.

The expectation is for the participant to complete the exposure phase having gained an idea for Sam's preferences for the usage of vague quantifiers such as "many" or "few". This expectation is verified in the test phase. More information and resources pertaining to the test phase can be found in the Test_Phase directory.
