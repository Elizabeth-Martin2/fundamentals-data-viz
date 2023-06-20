## Week 1 Discussion - Data & Goals
The dataset I have chosen to use is from the [Stanford Open Policing Project](https://openpolicing.stanford.edu/).  They collect data regarding traffic stops across the United States.  They also discuss their analysis methods and provide tutorials to duplicate their findings. Some of the key attributes of the data include Stop date, time, & location, driver race, age, & sex, search conducted, contraband found, citation or warning issued, arrest made, and reason for stop.  Not every dataset has all these attributes, and some of the datasets are enormous.  I will be using the dataset for San Antonio, Texas, which contains the majority of these properties.

Some questions I would like to answer: 
	1. Racial diversity of San Antonio
	2. Any existing biases
		a. As a <insert race, gender, age> person, how likely are you to be pulled over in San Antonio?
		b. How do the different factors affect likeliness to be pulled over?

The creators of the Stanford Open Policing Project detail some of their findings on the webpage under "Findings", but I think their visualization methods are difficult to understand.  Using the sizing differences in the outcome test doesn't provide any extra information and I still struggle to understand what it is trying to convey.  Otherwise, they are interactive, allowing the user to click on the datapoints and reveal more information, but that's the extent.  Their focus is on the race of the driver, and they even focus on the comparison between black, white and hispanic.  I'd like to expand that to ages & genders.  I also think it would be helpful to compare the sample data with the population to get a better understanding of my findings.

## Week 2 Discussion - Prototypes
Goal 1: Explore racial diversity of San Antonio
- What does a task seek to learn about the data: visualize the racial diversity of the city of San Antonio
- Who is executing the task: data scientists (us)
- When is the task performed: this should be the first visualization in our analysis 
- Why is a task pursued: to get a fundamental understanding before looking deeper into our other goals
- How is a task conducted: identify racial groups in the dataset then create a visualization
- Where does the task operate: the population of San Antonio 

Goal 2: Identify any biases / discrimination regarding race, gender, & age 
- What does a task seek to learn about the data: understand if there are any underlying biases causing police officers to pull over one group of people more than another
- Who is executing the task: data scientists (us)
- When is the task performed: now that we have an understanding of the racial diversity of San Antonio, we can look at how each group is currently treated.  This will be the second stage of our analysis
- Why is a task pursued: to explore the hypothesis of biases regarding race, gender & age
- How is a task conducted: by comparing the number of incidents and outcome for one group compared to another.  Assuming there is no bias, the rate of contraband found on searched <insert racial minorities / gender / age group> should be the same as the alternative corresponding groups of drivers. 
- Where does the task operate: in the comparison between races, genders & age groups

Findings: As a part of this process, I am thinking now it would be helpful to perform a similar analysis from Goal 1 but applied to age & gender 

## Week 3 Discussion - Evaluation

- The target question you want to answer: Do these visualizations provide a clear and intuitive way to explore the traffic stop data?
- The people you would recruit to answer that question: A mixed group of people would be best to answer this question.  On one side, you would want police administration to review the visualizations because they are very familiar with the scenarios and could use this tool to coach their officers and teach them better behaviour.  It would also be helpful to have inexperienced people (i.e., civilians) reviewing the visualizations because they could give you a fresh perspective and insight to the clarity of the tool.
- The kind of measures you would use to answer your question & what these measures would tell you about the core question: Insight depth - I would like to assess what the person thinks about traffic stops and any existing biases before they interact with my visualizations.  I'd then observe them as they interact with the visualizations, and assess them once more about their findings.  This would tell me if my visualizations were a valuable learning tool
- The approach you will use to answer that question: The approach I would take would be a formal experiment so I could hear what users were thinking and see how they are interacting with the visualizations
- How would you instantiate those methods: I would provide the participant a survey before and after using the visualization (an interview could also be used to gather their feedback, but surveys would be more scalable for larger participant groups)
- What criteria would you use to indicate that your visualization was successful: The goal of these visualizations is to teach and show that police officers have a long way to go before everyone is treated equally and without bias.  This is why I would want to assess the participants before using the tool to rate their existing knowledge, then again after using the tool to see what they learned.  If their answers have changed, they've learned something.  If their changed answers reflect the findings from the data, that would be a successful indicator.


## Sources
1. Stanford Open Policing Project - https://openpolicing.stanford.edu/
  > Vehicular traffic stop data
2. Census Reporter - https://censusreporter.org/profiles/16000US4865000-san-antonio-tx/
  > Population data conveniently formatted (original data from the US Census)
