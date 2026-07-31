**Information about the Test_Phase directory:**

Contains all the resources, documents and code pertaining to the exposure phase of the experiment, including:

- Videos of the cartoon character Chloe (guiding the participant through each trial by focusing their attention on the relevant element of the screen, posing questions, and either validating or correcting their responses) and the cartoon Character Sam (providing one-line descriptions of the gumball machine, each of which have two versions: one in which white noise blocks out the quantifier in the description, and one that remains unaltered). 
- CSV file used by the code to generate trials.
- Javascript code for use on the PCIbex farm.
- Script containing the interactions and responses of the characters during the Test Phase, available in the Test_Phase directory as a file named "TP_Script".

Elements absent from this directory that are still used in the exposure phase trials include:

- The square, circle and triangle button animations.
  - The participant will select one of the buttons to indicate "yes" or "no", respectively.
  - These video animations can be found in "Buttons" which is available as a separate folder in the main branch.
- The images of the gumball machine.
  - These can be found in "Gumball_Machines" which is available as a separate folder in the main branch.

**Information about the Test Phase:**

The test phase is the fourth and final phase of the experiment to determine if children (North-American, of ages 5-8) possess the capacity for speaker adaptation. Speaker adaptation, here, is the linguistic phenomenon in which the recognition of speaker's speech preferences with the respect to the usage of certain words produces a more fine-tuned interpretation of their speech in the listener. In this experiment, we focus specifically on speaker preferences with respect to the vague quantifiers "many" and "few". These vague quantifiers describe amounts and carry meanings that are often context-dependent and vary from individual to individual (thus, making them vague). The children are exposed to the speaker's preferences with respect to the vague quantifiers in the exposure phase, and the test phase tests if they've learned (i.e., recognized and adjust their own interpretations) these preferences.

Each trial follows the following format:

- An image of a gumball machine with a particular ratio of blue gumballs to orange gumballs is printed onto the screen.
- The cartoon character Chloe, standing to the left of the image, focuses the participant's attention on the image before directing it to Sam, who is standing to the right of the image.
- Sam provides a one-line description of the gumball machine in which the quantifier is blocked out using white noise.
- Chloe prompts the participant to respond with "many" or "few" (when the displayed ratio is 20/40/60/80) or "all" or "none" (when the displayed ratio is 0/100). These options are presented by the buttons printed below.
  - For the first trial in each category, Chloe provides guidelines on what the buttons stand for and how the participant may respond by selecting them. We incorporated these orally provided instructions as we cannot rely on the children's reading/writing abilities for any aspect of this experiment.
- The participant responds by selecting the button of their choice. The square button will stand for "many" (for 20/40/60/80 category) and "all" (for 0/100 category). The circle button will stand for "few" (for 20/40/60/80) or "none" (for 0/100). The triangle button will stand for "not sure" (to prevent forced answers).
- Chloe will let the participant know if they were right or wrong (or say "I see" for the "not sure" button press)
- Sam will provide the right answer to the participant by repeating his one-line description again but with the quantifier intact.

There are 18 trials in total. Trials using the quantifiers "all" and "none" are accompanied by the ratios 0 or 100, i.e. Trials using the quantifiers "many" and "few" are accompanied by the ratios 20, 40, 60, or 80, and they are interspersed by "all"/"none" trials, which act as attention checks. The counts for the different categories of trials are as follows:

Ratio 100 - 2
Ratio 0 - 2
Ratio 20 - 2
Ratio 80 - 2
Ratio 40 - 5
Ratio 60 - 5

Here, 100/0/20/80/40/60 refers to the percent of gumballs of one colour with respect to the other colour. 20 percent means 20 percent of the gumballs are blue, if the question targets blue gumballs, or 20 percent are orange, if the question targets orange gumballs.

A within-subject design is used in terms of the target colour, i.e., whether the question is addressing the amount of orange gumballs or the amount of blue gumballs. The trials shuffle between orange and blue for each participant. A between-subject design is used in terms of the speaker condition, i.e., whether the character embodies speaker 1 or speaker 2. No participant will be exposed to both conditions.

If the participant possesses speaker adaptation abilities, the expectation is for them to have recognized Sam's threshold from the exposure phase and correctly predict the quantifier Sam would use to describe the same percentages in the test phase. If the participant was exposed to Speaker 1 in the exposure phase, upon coming across a trial that targets orange with 40% orange gumballs, the expectation is for them to choose "many". If they were exposed to Speaker 2, the expectation is for them to choose "few". More information and resources pertaining to the exposure phase can be found in the Exposure_Phase directory.

