# vaccine_ad_campaigns
## 1. Demographics Data

The dataset simulates information on various demographic variables for 5000 respondents:

- **Age**: Randomly generated between 18 and 65.
- **Income**: Simulated based on age, with different income levels for different age ranges
- **Education**: Simulated based on age with probabilities for:
  - Middle School 
  - High School
  - Bachelor's
  - Master's
  - PhD
- **Marital Status**: Simulated based on age with probabilities for:
  - Single
  - Married
  - Divorced
- **Children**: Based on marital status, with "Single" individuals less likely to have children
- **Race and State**: Randomly assigned to each respondent from predefined lists

## 2. Baseline Questions

- **Vaccination Status**: The initial vaccination status is determined based on education and income, with higher vaccination rates for those with higher levels of education and/or higher income
- **Reasons for Vaccination or Not**: The reasons for taking or not taking the vaccine are randomly assigned based on vaccination status.
  - Reasons for Vaccination: "Health reasons", "To Travel", "Required by work", "Influenced by family and/or friends"
  - Reasons for no Vaccination: "Health reasons", "Safety concerns", "Distrust of it", "Don't believe it is effective", "Religious reasons"
- **Tested positive for COVID-19**: Whether the individual has tested positive for COVID-19 is determined based on vaccination rate, with a higher chance of testing positive if unvaccinated
- **Worries about COVID-19**: Respondents' worries about getting COVID-19 and the long-term COVID-19 and the COVID-19 Vaccine are based on a scale of 1-5, where: 1. "Not worried at all", 2. "Slightly worried", 3. "Moderately worried", 4. "Very worried", 5. "Extremely worried", with the long-term worries determined based on vaccination status
- **Immunocompromised Status**: Randomly assigns respondents to be immunocompromised or no
- **Vaccination for Other Diseases**: Simulated responses for previous vaccinations, with answers "Yes, for all or almost all", "Yes, but only a few diseases", "Unsure", "No"
- **Vaccination Mandate Beliefs**: Simulated responses for whether or not participant believes vaccination should be mandated, determined based on vaccination status with answers "Yes, for everyone", "Yes, but only for certain groups", "No, it should not be mandatory", "Unsure"

## 3. Random Assignment
Respondents are randomly assigned to one of the three groups, with one-third in each group. 
- Reason: Exposure to Facebook ad campaign that appeals to reason
- Emotion: Exposure to Facebook ad campaign that appeals to emotion
- None: Control, exposed to neither Facebook ad campaigns

## 4. Endline Questions
The endline survey modifies responses based on whether the respondent was exposed to a "Reason" or "Emotions" campaign. Out of the 5000 participants who responded to the initial baseline survey, 4500 of them responded to the endline survey. I made the assumption that the Facebook ad campaign was conducted over a few weeks. 
- **Vaccination Status**: Higher for all three assignment groups, with participants in the reason group who were not initially vaccinated being the most likely to change their answer to yes, followed by the emotions group
- **Tested positive for COVID-19**: Higher than baseline, with participants who were not vaccinated at the baseline being more likely to test positive than participants who were vaccinated at the baseline
- **Worries about COVID-19**: Participants exposed to the Reason and Emotion campaign were less worried about the long-term effects of COVID-19 and the COVID-19 Vaccine

## 5. Graphs and Figures
1. **Vaccination Rates (Baseline vs. Endline)**: Tables and graphs with vaccination rates at baseline and endline across each assignment group and across each assignment group by education level. 
2. **Worries about COVID-19**:
- Tables and graphs displaying average worry levels about COVID-19 and the COVID-19 vaccine across assignment groups.
- These worry levels are further grouped by:
  - Vaccination status at baseline
  - Gender
  - Education level
