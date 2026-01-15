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
The purpose of the survey is to assess satisfaction for different aspects of the respondent's job, including overall satisfaction, in order to pinpoint exactly which factors may be leading to low employee satisfaction and therefore high turnover (and thus what at the company might need to be changed). This survey will be administered to the full range of positions throughout the company instead of only the entry-level positions (see sampling strategy below) in order to better identify issues that are specific to only the entry-level positions (where the high turnover is happening). This survey is targeted to people still working at the company, rather than people who have already quit, since people no longer with the company may be harder to contact or may be less inclined to respond, and if we want to use our survey results to improve conditions at the company, it likely makes more sense to collect data from people who would actually benefit from those changes.
```

Describe your target population, sampling frame, sampling units, and observational units:
```
My survey will use a stratified sampling design, where the strata are different salary ranges at the company across all departments (e.g. all entry-level positions, all mid-level positions, all senior positions), and a certain number of respondents are randomly sampled from each of the salary ranges to take the survey via forms sent over email. Stratified sampling makes sense for this scenario because the employees at the company can easily be divided into strata based on salary data which should be available to Human Resources, and since we know that the turnover is happening across many different departments but specifically in lower-level positions, we might expect employees in different departments with similar salaries to have more similar job satisfaction than employees in the same department but very different salaries. The target population here is the entire company (we're interested in the lower-level positions, but also sampling more senior positions lets us identify trends that are specific to lower-level positions), and the sampling frame is everyone in the company with an email address that's available to the Human Resources Department. The sampling units and observational units here are both just the individual employees (since we're sampling from every stratum instead of randomly sampling strata). Enough people in each salary range should be sampled in order to capture all of the different departments at the company.
```

Your 5-10 question survey:
```
(These 3 questions are open-ended, allowing the respondent to enter anything)
1. Which department of the company are you employed in?
2. How many years have you worked at this company, in any position?
3. Approximately how much is your current annual salary at this company?

(These 5 questions have the following options: Highly unsatisfied, Moderately unsatisfied, Neutral, Moderately satisfied, and Highly satisfied)
4. How satisfied are you with your current salary?
5. How satisfied are you with the benefits you receive at this company (e.g. health insurance)?
6. How satisfied are you with your current workload (how much work you are expected to perform on a daily basis)?
7. How satisfied are you with with your work environment, including interactions with other employees?
8. Overall, how satisfied are you with your current position at this company?

(These 2 questions are open-ended, allowing the respondent to enter anything)
9. Are there any aspects of your current position not mentioned above that you are unsatisfied with? If so, include them here.
10. Are there any changes you would like to see at this company that would address any areas of dissatisfaction touched on in this survey? If so, include them here.
```

## Part B - Survey Evaluation:

Identify and describe survey features:

```
1. Sample type: Stratified sampling - the 10 Canadian provinces were divided into 27 strata. Random samples of households were taken from each stratum based on available telephone numbers, and a random eligible individual from each household was surveyed. "Rejective sampling" was also used, where some respondents who were not volunteers were randomly chosen to be excluded from the full survey.
2. Sample size: The total number of respondents (excluding rejected non-volunteers) was 16,149.
3. Target population: Everyone 15 years old or older in all 10 Canadian provinces, except for full-time residents of institutions.
4. Sampling frame: Households with telephone numbers available to Stats Canada. The Address Register, a list of all households in the 10 provinces, was used to group together phone numbers known to belong to the same household.
5. Survey mode(s): Surveys were completed either through an electronic questionnaire or over the phone (computer assisted telephone interviewing), in either English or French.
6. Timeline: Data was collected between September 4th 2018 and December 28th 2018.
7. Response rate: The response rate was 41.9%.
8. Weights: Person-level weights were used, for example to account for the fact that a certain amount of non-volunteers were randomly rejected, and to try and make sure that weighted distributions of responses (e.g. income, age, sex) matched known distributions for the province. Bootstrap weights were also calculated for variance estimation.
9. Data processing: Responses out of the scope of the survey, as well as non-responses, were dropped. Imputation was used to fill in certain missing values. Where possible, personal income data was taken from a respondent's linked tax records. Person-level weights were calculated, as mentioned above. 
10. Cleaning, imputation, etc: Checks were done where possible to make sure that the survey data was consistent with itself, e.g. comparing the respondent's given age to their given date of birth. If, during the survey, a given data point was found to be outside of the valid range of values, the respondent was asked to correct this error where possible. For certain variables such as personal and family income, non-responses were imputed by using the value from the most similar "donor" record.
11. Sources of error: The random sampling data collected here is subject to sampling error, meaning that it likely does not perfectly represent the full population. There are also coverage errors since the sampling frame does not perfectly match the target population, e.g. houses with eligible respondents but without available telephone numbers would not be sampled. Errors can also come from respondents not responding to certain questions, responding with incorrect information, or responses being incorrectly entered by the interviewer. 
12. Limitations, known biases, etc: In addition to the above sources of error (e.g. inability to sample households without telephones, meaning that those individuals will be excluded), one source of bias is that questions about income are known in general to have high non-response rates (e.g. if someone is uncomfortable with sharing their personal income or doesn't know their exact household income). In these cases, if income data are unable to be obtained from linked tax records, the income data would have to be imputed. Also, if this survey is intended to understand Canada as a whole, sampling from only the 10 provinces is a limitation because respondents from the 3 territories may have responses that tend to differ from the rest of the country, and so excluding them is another source of bias.
13. Link to documentation and any additional sources used: My sources are the Stats Canada documentation found at this link (https://www23.statcan.gc.ca/imdb/p2SV.pl?Function=getSurvey&Id=796234), as well as the "Public Use Microdata File User Guide" found in the ZIP file located here (https://www150.statcan.gc.ca/n1/pub/45-25-0001/cat5/c33_2018.zip).
```

## Rubric

-	All required components are present and complete **Complete / Incomplete**
-	Choice of sampling strategy for Part A is justified and related to survey purpose **Complete / Incomplete**
-	Information for Part B is complete and correct **Complete / Incomplete**

## Submission Information

🚨 **Please review our [Assignment Submission Guide](https://github.com/UofT-DSI/onboarding/blob/main/onboarding_documents/submissions.md)** 🚨 for detailed instructions on how to format, branch, and submit your work. Following these guidelines is crucial for your submissions to be evaluated correctly.

### Submission Parameters:
* Submission Due Date: `23:59 - 14 January 2026`
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
