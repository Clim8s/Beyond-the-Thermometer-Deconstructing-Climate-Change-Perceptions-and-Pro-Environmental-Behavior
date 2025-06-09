
------------------------------
Column Descriptions
------------------------------

### Dataset Description

This dataset contains responses from a large-scale survey assessing demographics, political and social attitudes, beliefs about climate change and conspiracy theories, and self-rated personality traits. Each row corresponds to a unique participant and their responses to a set of fixed questions.

---

### Column Descriptions

#### Demographic Variables

- UserID  
  An anonymized identifier for each participant.

- Gender  
  Self-identified gender (e.g., Male, Female, Other, Prefer not to say).

- Region of Birth  
  Country or geographical region where the respondent was born.

- Region of Residence  
  Country or region where the respondent currently lives.

- How long ago did you move to your current country of residence?  
  Number of years since immigration (if applicable).

- Do you have children?  
  Indicates whether the respondent has children.

- Education Level (Highest achieved or currently pursuing)  
  Highest level of education completed or currently being pursued (e.g., High School, Bachelor's, Master's).

- Job Status  
  Current employment status (e.g., Employed full-time, Student, Unemployed).

- Job Role  
  General job domain or profession (e.g. Engineering, Marketing).

- Job Level  
  Seniority or professional level (e.g., Entry level, Manager, Executive).

- Topic(s) of interest  
  Topics selected by the respondent as personally important or interesting.

- Social Media Usage  
  Frequency and context of using social media.

#### Climate Change Attitudes and Beliefs

These questions assess concern, understanding, and attitudes toward climate change, government policy, and personal experience. Responses are typically on a Likert scale (e.g., Strongly agree to Strongly disagree):

- Concern about policies increasing cost of living
- Importance of national leadership in innovation
- Patriotism means leaving the country better than found
- Political orientation (liberal–conservative spectrum)
- Beliefs about social hierarchy
- Optimism or pessimism about the future
- Opinion on immigration levels
- Belief that global warming is occurring
- Belief about the cause of global warming
- Belief about scientific consensus on climate change
- Perception of climate change's effect on weather
- When global warming will begin to cause harm
- Perceived harm to:
  - Plants and animals
  - Future generations
  - Developing countries
  - Own country
  - Oneself personally
- Personal experience of global warming
- Policy preferences and support for:
  - Renewable energy research
  - Carbon taxation
  - Tax rebates for clean energy
  - Emissions limits on coal plants
  - Fossil fuel drilling (on/offshore)
- Perception of responsibility by:
  - Corporations
  - The President
  - Congress
  - Governor
  - Local officials
  - Citizens
- Priority questions for policymakers
- Support for 100% clean energy by 2050
- Frequency of discussing or hearing about global warming
- Severity of personal effects
- Willingness to pay higher bills for renewables
- Personal responsibility for future generations

#### Conspiracy Beliefs

Statements reflecting belief in conspiracy theories. Respondents rate agreement or belief level:

- Belief in virus/disease conspiracies
- Belief in concealed information by authorities
- Belief in small groups manipulating world events
- Belief in staged or concealed terrorist acts
- Belief in experimentation on the public
- Suppression of technology
- Secret political control
- Alien contact concealment
- UFO misinformation
- Government involvement in murders
- Mind control and technology
- Scientific manipulation or fraud

#### Personality (Big Five Traits)

These statements assess self-perception across five personality domains:

- Openness to Experience
  - "I have an active imagination."
  - "I have few artistic interests." (reversed)

- Conscientiousness
  - "I do a thorough job."
  - "I tend to be lazy." (reversed)

- Extraversion
  - "I am outgoing, sociable."
  - "I am reserved." (reversed)

- Agreeableness
  - "I am generally trusting."
  - "I tend to find fault with others." (reversed)

- Neuroticism
  - "I get nervous easily."
  - "I am relaxed, handle stress well." (reversed)

#### Unknown or Placeholder Questions

- Question 93 – Question 97  
  Placeholder or unnamed questions pending labeling or removing.

---

### Data Format Notes

- Data types: Categorical, Binary, Likert scale, or Free Text
- Missing values may occur where responses were skipped
- Each row = one participant’s complete set of responses

---

### Intended Usage

This dataset is suitable for:

- Exploratory data analysis (EDA)
- Supervised machine learning (e.g., classification)
- Correlation studies (e.g., personality vs. beliefs)
- Visualization of opinion trends by demographic group

------------------------------
Format Notes:
------------------------------
- Responses may be categorical, binary, Likert-scaled (e.g., Strongly Agree to Strongly Disagree), or free text.
- Missing values may be present for skipped or inapplicable items.
-----------------------------------------------------------------------------------------------------------------------------------------------------------------------