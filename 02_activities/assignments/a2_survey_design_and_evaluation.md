# Assignment: Questionnaire Design and Sample Evaluation

## Requirements

The goal of this assignment is to practice developing and evaluating sampling materials.

### Part A - Survey Design:

Select one of the scenarios below and design a survey to meet the need(s) outlined in the prompt.

1.	In two to three sentences, describe the purpose of your survey
2.	Describe your target population, sampling frame, sampling units, and overall sampling strategy.
3.	Write a 5-10 question survey to address your chosen scenario below.

##### Scenarios
1.	You work in the Human Resources Department at a large tech company. Over the past few months, the company has been experiencing a high turnover rate across many of its departments, specifically within the entry- and lower-level positions. The company wishes to understand why this turnover is happening, and what changes need to occur to improve employee satisfaction.
2.	You work for a Canadian national political party during a federal election. Throughout the campaign period, your party has seen relatively high approval ratings, but an opposing party is also polling favorably and may still have a chance to win the election. You are one month away from the election and you want to understand what voters want from your party and its leader in order to maintain your lead and eventually win the election.
3.	You are a student researcher in the sociology department at the University of Toronto. You are working on a research project that concerns the relationship between music taste and age. This involves both comparisons between different people of different ages and comparisons of the same individual at different ages during their lifetime. You wish to understand to what extent age influences music taste, specifically as it relates to perceptions of popular music. Your results will be written into an academic paper that you hope to publish.

### Part B - Survey Evaluation:

For the **Canadian General Social Survey on Giving, Volunteering, and Participating, 2018 (cycle 33)**, conducted by Statistics Canada find any and all available documentation for the data gathered and identify and describe the survey features indicated below.

1. Sample type
2. Sample size
3. Target population
4. Sampling frame
5. Survey mode(s) 
6. Timeline
7. Response rate
8. Weights
9. Data processing
10. Cleaning, imputation, etc
11. Sources of error
12. Limitations, known biases, etc
13. Link to documentation and any additional sources used


# Your Changes

## Part A - Survey Design: 

The number of your chosen topic: `#`

Describe the purpose of your survey:
```
The purpose of this survey is to understand voter priorities, impressions of the party leader, and what policy positions might persuade undecided voters. Results will be used to inform campaign strategy and messaging in the final month before the election. 
```

Describe your target population, sampling frame, sampling units, and observational units:
```
The target population is anyone over the age of 18 who is eligible to vote in a canadian election. The sampling frame consists of registered eligible voters drawn from Elections Canada's official voter registry, supplemented by random digit dialing to capture eligible voters who may not be on the registry. The sampling units is individual eligible voters selected from the sampling frame, with the observational units being the individual voters who respond to the survey, as each respondent's answers are what is being measured and analyzed. A stratified probability-based sampling strategy will be used, with Canada's provinces and territories serving as strata to ensure regional representation. Within each stratum, voters will be randomly selected from the sampling frame. Post-stratification weights will be applied by region, age, gender, and language to align the sample with the broader Canadian electorate as measured by the most recent Census.
```

Your 5-10 question survey:
```
1. What is your age range, province of residence, and preferred official language? 

Age: Under 25 / 25–44 / 45–64 / 65+
Province/Territory: ___
Preferred language: English / French / Other
What is your gender identity: (open to be filled)

2. Which of the following issues is most important to you in this federal election? (Multiple choice, select one)

Cost of living 
Healthcare
Housing affordability
Climate change
Immigration
Public safety
Other (please specify): ___

3.How would you rate your overall impression of the Party Leader

Very positive
Somewhat positive
Neutral
Somewhat negative
Very negative
I do not know enough to say


4. How well do you think the Party understands the concerns of people like you?

Very well
Somewhat well
Not very well
Not well at all
Unsure

5. How do you primarily get your news and political information? (Multiple choice, select all that apply)

Television / Social media / Newspapers / Radio / Online news sites / Word of mouth / Other


6. Compared to the opposing party, how well do you feel the Party addresses the issues that matter most to you? (Likert scale)

Much better / Somewhat better / About the same / Somewhat worse / Much worse

7. What would make you more likely to support [Party Name] in the upcoming election?

A clearer plan for lowering the cost of living
A stronger housing affordability plan
More detail about healthcare policy
A stronger climate/environment plan
More confidence in the party leader
More confidence in the local candidate
A negative impression of another party
Nothing would make me more likely to support them
Other: ________

8. Is there anything [Party Name] or its leader could do differently that would make you more likely to support them? (Open-ended)


9. How certain are you about your current voting choice?

Very certain
Somewhat certain
Not very certain
Not at all certain
I am currently undecided

10. write your question here... (optional)
```

## Part B - Survey Evaluation:

Identify and describe survey features:

```
1. Sample type: Stratified probability-based sample using simple random sampling without replacement within each stratum. Rejective sampling was also used to oversample volunteers due to their lower prevalence in the population.

2. Sample size: The target was 20,000 respondents; the actual final sample was 16,149 respondents 

3. Target pop: All persons 15 years of age and older living in private households across Canada's ten provinces. Excludeding residents of Yukon, Northwest Territories, and Nunavut, and full-time residents of institutions.

4. Sampling Frame: A combined frame using: (1) lists of landline and cellular telephone numbers available to Statistics Canada, and (2) the Address Register (AR) which is a list of all dwellings in the ten provinces. About 86% of telephone numbers were linked to the AR and the remaining 14% were included separately to maximize household coverage.

5. Survey Mode: there were two modes in which the survey was administered. for the 2018 GSS GVP were collected electronically as a self-completed questionnaire (rEQ) as well as via computer assisted telephone interviews (iEQ). Respondents were interviewed in the official language of their choice. Proxy
interviews were not permitted. Online responses accounted for 51.8% of completed responses.

6. Timeline: Data were collected from September 4 to December 28, 2018

7. Responce rate: The Overall response rate was 41.9%.

8. Weights: Each respondent was assigned a final person weight (WGHT_PER). Weighting involved multiple steps: initial probability-of-selection weight, non-response adjustment (three stages), person weight calculation, rejective sampling adjustment, and raking ratio adjustments to match external totals by stratum (geography), province-age-sex, and income distribution. The guide also mentions bootstrap weights that were provided for variance estimations.

9. Data Processing: Responses to survey questions were entered directly into computers by respondents who self-completed the electronic questionnaire (rEQ) and by interviewers who completed interviews with respondents by telephone (iEQ). Both respondents and interviewers used the same data capture system to complete the questionnaire. The data capture program allowed a valid range of codes for each question, had built in edits, and automatically followed the flow of the questionnaire. The data output was encrypted and transmitted electronically to Ottawa. Processing steps also included combining daily transmissions into a raw file, removing duplicates and out-of-scope records, flow editing using a top-down strategy, coding of write-in responses using standard classification systems (NAICS, NOC, ICNPO), and creation of derived/combined variables.

10. Cleaning: Missing data were handled through donor imputation, a nearest-neighbour method where records with missing values are matched to the most similar complete record (donor) based on shared characteristics. Imputation addressed three types of non-response: complete, item, and partial. It was carried out in nine steps covering personal income (18.1% of records imputed), family income (18.3%), volunteering hours, and donation variables. Income data were primarily obtained by linking to 2017 T1FF tax records for 81.9% of respondents. For the PUMF, donation values were also perturbed and rounded to protect respondent confidentiality. 

11. Sources of error: The guide identifies both sampling and non-sampling error. Sampling error occurs because the survey is based on a sample rather than a census of the entire target population. Statistics Canada recommends using bootstrap weights to estimate sampling variability, standard errors, confidence intervals, and coefficients of variation. More guidelines are given on how to deal with sampling error with their policies. Non-sampling error can include coverage error, non-response error, response error, and processing error. Coverage error can occur because the surveyed population does not perfectly match the target population. For example, households without telephone service or without telephone service covered by the frame were excluded from direct sampling. Non-response error can occur when households or selected individuals do not respond, and response error can occur when respondents misunderstand questions, misremember information, or provide inaccurate answers. Processing error can occur during coding, editing, imputation, or tabulation. Statistics Canada used quality-control measures such as trained interviewers, questionnaire testing, built-in edits, processing checks, and weighting adjustments to reduce these errors. 

12. Limitations: The primary limitation was that the sample size was very limited by excluding residents of the three territories as well as institutional residents entirely from having an impact on their ultimate sample sizes. Another limitation results from the fact that there were unequal sampling fractions across strata within a stratified sampling design. Some geographic areas were over-represented in relation to their geographic population size, while other geographic areas were under-represented. Therefore, the unweighted sample must not be considered representative of the Canadian population, which includes all individuals aged 15 or older. One other limitation associated with this study relates to coverage error. Households that do not have a telephone or do not have telephone service included in the frame were excluded as a part of the overall surveyed population. Although adjustment of survey weights was made so as to account for the sampled population’s overall profile, there is significant potential for residual bias to arise if there are any differences between respondents and both excluded and non-respondent groups within the sampled population. It is also important to note that non-response bias is a major concern given the overall response rate of this study (i.e., 41.9%). Non-response weighting was implemented to the greatest extent possible to eliminate non-response bias by applying various type. Due to an overall response rate of 41.9%, there is added concern regarding the possibility of nonresponse bias affecting the results. Adjusting weights using several administrative records (income and household structure) is one method that Statistics Canada has used in order to help mitigate any effects of nonresponse, but because of the limitations of using weights alone, there will still be forms of bias present in the final results. There are other limitations associated with income-related variables as well. Personal income questions were not directly asked in the 2018 survey; rather, Statistics Canada attempted to link respondents to 2017 T1FF tax data to obtain the income of each respondent (provided they had no objections). Of those who provided an income value, 81.9% of respondents did so; 18.1% (the remaining) were income-imputed. Of households surveyed, 81.7% of them provided the family income and were therefore able to be linked to the family income imputed for 18.3% of households. Due to the relationship between income and charitable giving/volunteering, this imputation of income should be considered a limitation when interpreting the results by income group. There are also all the sources of error described above that I will not be re typing here.

13. Links: All of the above information was more or less taken directly from their USER guide which I downloaded through a zip file

https://www150.statcan.gc.ca/n1/pub/45-25-0001/cat5/c33_2018.zip

https://www150.statcan.gc.ca/n1/en/catalogue/45250011

https://www150.statcan.gc.ca/n1/daily-quotidien/210126/dq210126h-eng.htm


```

## Rubric

-	All required components are present and complete **Complete / Incomplete**
-	Choice of sampling strategy for Part A is justified and related to survey purpose **Complete / Incomplete**
-	Information for Part B is complete and correct **Complete / Incomplete**

## Submission Information

🚨 **Please review our [Assignment Submission Guide](https://github.com/UofT-DSI/onboarding/blob/main/onboarding_documents/submissions.md)** 🚨 for detailed instructions on how to format, branch, and submit your work. Following these guidelines is crucial for your submissions to be evaluated correctly.

### Submission Parameters:
* Submission Due Date: `23:59 - 09 February 2026`
* The branch name for your repo should be: `assignment-2`
* What to submit for this assignment:
    * This markdown file (a2_survey_design_and_evaluation.md) should be populated and should be the only change in your pull request.
* What the pull request link should look like for this assignment: `https://github.com/<your_github_username>/sampling/pull/<pr_id>`
    * Open a private window in your browser. Copy and paste the link to your pull request into the address bar. Make sure you can see your pull request properly. This helps the technical facilitator and learning support staff review your submission easily.

Checklist:
- [ ] Create a branch called `assignment-2`.
- [ ] Ensure that the repository is public.
- [ ] Review [the PR description guidelines](https://github.com/UofT-DSI/onboarding/blob/main/onboarding_documents/submissions.md#guidelines-for-pull-request-descriptions) and adhere to them.
- [ ] Verify that the link is accessible in a private browser window.

If you encounter any difficulties or have questions, please don't hesitate to reach out to our team via the help channel in Slack. Our Technical Facilitators and Learning Support staff are here to help you navigate any challenges.
