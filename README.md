# A3: U.S. COVID Trends

## 1. Overview
In many ways, we have come to understand the gravity and trends in the COVID-19 pandemic through quantitative means. Regardless of media source, people are consuming more epidemiological information than ever, primarily through reported figures, charts, and maps. 

This assignment is your opportunity to work directly with the same data used by the _New York Times_. While the analysis is guided through a series of questions, it is your opportunity to use programming skills to ask more detailed questions about the pandemic.

You'll load the data directly from the [New York Times GitHub page](https://github.com/nytimes/covid-19-data/), and you should make sure to read through their documentation to understand the meaning of the datasets. 

## 2. Critical Analysis & Reflection: Before You Code
As you know, the first step in a data science project is to investigate the domain. Accordingly, please begin this assignment by carefully reviewing [New York Times GitHub page](https://github.com/nytimes/covid-19-data/) and 
reading this [FAQ](https://www.nytimes.com/interactive/2020/us/about-coronavirus-data-maps.html) about the data. Working with _Data Feminism_ (Catherine D'Ignazio and Lauren Klein, 2020), consider the following questions: 
* What is the _New York Times_' goal? 
* Where does the data come from? Is the data reliable? 
* Who are the direct and indirect stakeholders?
* What values are implicated by this dataset and system? 
* What issues related to "power" arise because of this dataset? 

After reading and considering these questions, please provide written responses to these two questons: 
* **R0a** Drawing on _Data Feminism_, and your study of the data, describe and discuss the _New York Times_' project. Discuss the social aspects of this project, focusing on stakeholders, values, and power. 


* **R0b** Review the visualizations that are found at the bottom of this [FAQ](https://www.nytimes.com/interactive/2020/us/about-coronavirus-data-maps.html). Document two _important_ questions that a person living in the U.S. could answer with these visualizations. Discuss the importance of these questions.

Note: Please write your answers below under the heading "Your Responses and Reflections."

## 3. Coding and Critical Analyis & Reflect: While You Code

### Getting Started
You should start this assignment by opening up the `analysis.R` script. The script will guide you through an initial analysis of the data. 

You will also find a file, named `rolling_windows.R`. Studing the code in the file will be helpful for some aspects of this assignment.

* **Coding prompts.** Complete the coding prompts in `analysis.R`.  Your goal is correct code that is readily understandable.
* **Reflection prompts.** Throughout the script, there are prompts labeled `REFLECTION`. Please write 1-3 sentences for each of these prompts below. Please strive for concise, clear, inclusive, and insightful writing. As appropriate, your writing should: 
   - Provide evidence (e.g., facts from the datasets, points from the New York Times documentation, etc.)
   - Give justification for your opinions
   - Genuinely reflect on your views.  

## 3. Critical Analysis & Reflection: After You Code
**R6a** Consider the many visualizations that can be created with this data set (see [FAQ](https://www.nytimes.com/interactive/2020/us/about-coronavirus-data-maps.html)) for many examples, which in the next few weeks, 
you will be able to create. Also, step back and reflect on the hard work that you have completed. 

Now, drawing on _Data Feminism_ comment on the importance of this data set. 

**R6b** Please briefly comment on one of these or similar questions: 
* What, if anything, made you curious?
* What, if anything, surprised you about your R coding work?
* What might you do the same or differently on your next data wrangling project? 

## Reflection Prompts 

**R0:** Critical Analysis & Reflection: Before You Code
* **R0a** ... 
The social aspects of this dataset were to provide information about Covid-19. This data set is drawn to people such as journalists,researchers, and programers. The information can be tested many different ways.This dataset provides a lot of detail about Covid-19 that people who are intersted in Covid-19 could learn a lot about. It was fascinating how many cases and deaths there were in certain places. This dataset can be very knowledgable to those who want to learn more about it. Journalists can include the graphs in articles that they make to talk about Covid and how it's changed peoples lives. 




(125 - 200 words, or more if needed)
* **R0b**
   - Question 1: How many more people 70+ are admitted to the hospital daily compared to people who are younger? People who are over 70+ can have more serious symptoms since they are older and have illnesses that can make them be hospitalized more. These people can be more at risk and their immune system isn't as good as people who are younger. Since their immune system as good and they are less mobile, more people over 70+ are admitted to the hospital daily. Younger people have a stronger immunity system which makes them less at risk at having to go to the hospital to get treated. Younger people have an easier time fighting off a virus and if they do get a virus it would be a pretty mild case compared to those who are are in their 70's whose bodies have a hard time fighting diseases and require a check up more often.
   
   - Question 2: How many times more likely is it for someone who is unvaccinated to die  
  versus the likeliness of those who are vaccinated to die? It is more likely for someone who is unvaccinated to die because they haven't gotten the proper vaccination they needed to properly fight off the virus. Since there are so many people in the hospital who are unvaccinated or not getting the proper medication they need. It makes the death toll rise. It is less likely for someone who is vaccinated to die because they got the vaccinations and recieved the proper medication they need to survive and it makes it less of a risk for them to die versus those who are unvaccinated who haven't recived their vaccinations and their bodies would have a harder time fighting off the virus and have a significantly more at risk. Those who are vaccinated have a better chance at living than those who are unvacciated. 
  
  
  


**R1:** Loading Data
* **R1a** ...  (bullet points are fine)
(a) Not all counties are shown because they are less than 10,000 whereas the state and country data everything is shown.

(b) All three data sets all have date, cases,and deaths.

(c) Fips is Federal Information Proccessing Standards and the numbers represent specifc location code for each location. 



**R2**: Exploratory Analysis
* **R2a** I learned that when I calculated the state, it came up with American Samoa. This told me that the dataset included American Territories not just states.  This tells me that it is important to test to your assumptions because often times your assumptions aren't correct. 

* **R2b** The county with the highest cases is Los Angeles whereas the location with most deaths is New York City, New York, so they are not the same location. I think that New York City didn't have as good of an infastructure as Los Angeles did so more people died. 

**R3**: Grouped Analysis
* **R3a** There are so many observations because it also includes American terratories as well as  the capital in addition to the 50 states. 

**R4**: Joins
* **R4.a**
(a) National and State were consistent but State and County were inconsistent. This told us that the source of the inconsistency was County

(b) In order to find the inconsistency, we can run a test to get the exact dates of the inconsistencies between the county and the other datasets.  


**R5**: Independent Exploration 
* No prompts

**R6**: Critical Analysis & Reflection: After You Code
* **R6a** 
There were many visualizations that could be created and to be able to see it in a graph was very interesting because you could really see which places had the most cases compared to the other counties/states. This dataset is important because it gives us a good look at what is happening around the U.S with Covid-19. The data is also important because it can be tested with many different approaches to see how effective different policies were at reducing Covid transmission and deaths.  
* **R6b** 
Something that made me curious was how many cases there were in the county with the most cases. I wasn't expecting to see such a big number. Something else that was made me curious about is why they added an American Territory within the state data, it was really interesting because it wasn't just  state data but it also included American Territories. 

