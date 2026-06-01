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

The number of your chosen topic: `1`

Describe the purpose of your survey:
```
The purpose of the survey is to understand the opinion that entry-level and low-level hires have on the company. With high turnover rates, there is an assumption that new-hires have a negative opinion of the company, which is to be assessed with this survey.
```

Describe your target population, sampling frame, sampling units, and observational units:
```
The target population is all past and current employees of the company, defined as entry-level or low-level. The sampling frame is all entry-level and low-level current employees of the company. Since we cannot survey employees who have left the company, the assumption is that some of the current employees will share the opinion of the those who have left. The sampling units, would be the employees which received the survey. In this case, I believe the observational units would be the same as the sampling units.
```

Your 5-10 question survey:
```
1. Are you happy with your position at the company?
2. Would you recommend a friend for a position at the company?
3. Would you consider the company a positive place to work?
4. Would you consider leaving the company in the near future?
5. Do you know of any significant issues within the company that impact your opinion? 
6. Would you define the corporate culture of the company as being a positive place to work?
```

## Part B - Survey Evaluation:

Identify and describe survey features:

```
1. The sample type in this case is a cross-sectional survey; a series of questions asked to the respondents.

2. 80,000 individuals were used, 60000 identified for the "regular sample" and 20000 additional members for the "oversample." The oversampled population was done due to increased funding for the survey.

3. All residents of Canada >15 years of age, that do not live the territories, or on First Nations reserves.

4. The sampling frame for the initial survey is every household as defined in the 2021 Census of Population. However a technique called "rejective sampling" was used to reduce the sampling frame. 

5. Responses to the survey were collected either through an electronic questionnaire or through a computer assisted telephone interview. 

6. The survey has a frequency of every 5 years.

7. The overall response rate of the survey was 40.9 % (including both the original and oversmapled populations).

8. The survey designers including a "WGHT_PER" variable which modifies the respondents responses based on factors such as the proportion of the total population each survey respondent represents, by income of the household, non-response bias, and non-sampling error. 

9. Data processing was performed in the context of error correction, where the social survey processing environment provided a general list of steps and utilities for processing the data to limit errors and ensure best practices.

10. Data imputation was performed using donor imputation where data are inputted in a missing respondents case, based on the responses of similar candidates. 

11./12. Numerous sources of error and biases were identified such as:
    - non-sampling error (ie. individuals who they could not contact, were not sampled, imperfect coverage, etc.)
    - non-response bias 
    - coverage error

13. All information came from this link: https://www23.statcan.gc.ca/imdb/p2SV.pl?Function=getSurvey&Id=1526823
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
