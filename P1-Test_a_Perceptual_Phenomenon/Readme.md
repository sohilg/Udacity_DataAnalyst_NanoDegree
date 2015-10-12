# Project 1: Test a Perceptual Phenomenon
#### Background information

In a Stroop task, participants are presented with a list of words, with each word displayed in a color of ink. The participant’s task is to say out loud the color of the ink in which the word is printed. The task has two conditions: a congruent words condition, and an incongruent words condition. In the congruent words condition, the words being displayed are color words whose names match the colors in which they are printed. In the incongruent words condition, the words displayed are color words whose names do not match the colors in which they are printed. In each case, we measure the time it takes to name the ink colors in equally-sized lists. Each participant will go through and record a time from each condition.

#### Stroop task Dataset: [View CSV](https://github.com/sohilg/Udacity_DataAnalyst_NanoDegree/blob/master/P1-Test_a_Perceptual_Phenomenon/stroopdata.csv)

#### Questions for investigation

##### 1.	Question 1: Identify variables in the experiment
The variables in the experiment are:
* **Independent Variable:** Word Condition (Congruent or incongruent)
* **Dependent Variable:** Time it takes to name the ink colors.

##### 2.	Question 2: Establish a hypothesis and statistical test
* **Ho Null Hypothesis:** Average Time taken to name the ink colors for both the word condition (Congruent/Incongruent) is not significantly different. **µ(Congruent) = µ(Incongruent)**
* **Ha Alternative Hypothesis:** Average Time taken to name the ink colors for both the word condition (Congruent/Incongruent) is significantly different. **µ(Congruent) ≠ µ(Incongruent)**
* **Statistical Test:**  **Paired T-test** because to test if the average time taken in two different word condition (Congruent/Incongruent) are equal or not.

##### 3.	Question 3: Report descriptive statistics
* **Congruent:** 
  * **Average** = 14.05
  * **Min** = 8.63; **Max** = 22.328 
  * **Median** = 14.3565 
  * **S.D.** = 3.6
* **Incongruent:**
  * **Average** = 22.01 
  * **Min** = 15.687; **Max** = 35.255 
  * **Median** = 21.0175 
  * **S.D.** = 4.8

##### 4.	Question 4: Plot the data 
From above Line Chart, we can see that the time taken to name in case of Incongruent word condition is consistently higher compared to the congruent word condition.

##### 5.	Question 5: Perform the statistical test and interpret your results 
We can see the t-statistic value of -8.0207 with a p-value of 4.103e-08 which is significantly less than 0.001.
Therefore, we can reject the Null Hypothesis that the average time taken to name the ink colors is not significantly different.


##### References:
 *	http://www.statstutor.ac.uk/resources/uploaded/paired-t-test.pdf
 * http://www.ats.ucla.edu/stat/mult_pkg/whatstat/choosestat.html
