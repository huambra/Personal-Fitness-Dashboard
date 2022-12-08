# Personal-Fitness-Dashboard
### A Data Analysis and Visualization Project
&nbsp;<br>
&nbsp;<br>
![Alt text](https://github.com/huambra/Personal-Fitness-Dashboard/blob/master/Visualizations/final-dashboard.jpg)

## Table of Contents

- [Project Description](#project-description)
- [Actions](#actions)
- [Results](#results)
- [Conclutions](#conclutions)
  
## Project Description

This is a personal project that has the goal of helping me understand how my habits can affect my physical health at a general level. You can find the final dashboard [here](https://docs.google.com/spreadsheets/d/1hwOEG-T5IJ6-9wilPffjGfQmaruxQwk0Lbe_f9g_1R0/edit?usp=sharing)

A few years ago, I had 2 surgeries within 6 months and I couldn’t move my body as I used to for over one year. This resulted in me being in the worst shape of my life and also having health-related issues since I was getting seriously underweight. A Little less than 2 years ago I decided that it was in my power to change my habits in order to get control over my body again. 

Since Covid hit us, I decided to start my focus on at-home training programs, and I found a company called “Adicto al fitness”. They specialized in house training with a platform that provides live workouts, pre-recorded videos, a nutrition calculator, healthy food videos, etc. An all-in-one solution to start a fitness journey at your own place. The first 3 months were really hard, but the results were visible right away, and that kept me motivated to keep on going. 

Months later, however, my body started to get used to the exercise, and although the program was perfect, I found it really tricky to keep track of my changes. This was due to the lack of a personal fitness dashboard, which is not provided by the app, but also from a lack of understanding of how my daily habits were affecting my body.

So I decided to create a simple solution(everything here was done only using Google tools), to generate data about my habits for over 75 days, and then analyze it and visualize it, in order to get a deeper understanding of my habits and improve upon them.
The Google Form is [here](https://forms.gle/gw3U9riPwjTN8U1j7), and the Google Sheet file is [here](https://docs.google.com/spreadsheets/d/1hwOEG-T5IJ6-9wilPffjGfQmaruxQwk0Lbe_f9g_1R0/edit?usp=sharing). 

## Actions
My role in the project was accessing the data, then transforming it in order to develop a dashboard, that would help me understand how my habits were affecting my weight.

First things first, I tried to keep th project very simple, so I used easy to use and free available tools from Google. I designed a form on Google forms, that I would have to fill in everyday in order to create the data for the project. Then I connected it to Google Sheets so I would get real time data inside a raw data file ready to be preprocessed. A tutorial on how to do this is [here](https://www.youtube.com/watch?v=507H7UGBsaU&ab_channel=SpreadsheetPoint).

After that was done, I started with the data transformation. Since everything was going to be handled under Google Sheets, there was not much preprocessing to do. However, I did have to make some changes to the raw data, first condensing food(breakfast, lunch, diner) into a single variable, and second, I  created a new column to store the key metric (optimal day). 

Then I started creating pivot tables to create the necessary charts for the dashboard. Once I had all the figures I needed, I put them into a different sheet and created the initial mockup of the dashboard.

![Mock up](https://github.com/huambra/Personal-Fitness-Dashboard/blob/master/Visualizations/mock-up.jpg)

I evaluated the mockup and decided to improve the dashboard by adjusnting things like legends, y-axis min and max values, gridlines, colors, styles, etc. The final result was the following: 
*to visualize the full dashboard click [here](https://docs.google.com/spreadsheets/d/1hwOEG-T5IJ6-9wilPffjGfQmaruxQwk0Lbe_f9g_1R0/edit?usp=sharing)

![Dashboard](https://github.com/huambra/Personal-Fitness-Dashboard/blob/master/Visualizations/final-dashboard.jpg)

## Results
First, I would like to explore the results of my 76 days experiment, starting with the fact that I was able to gain weight over that period of time. More importantly, due to the right diet, I was able to gain a little over 2 Kg of lean muscle, and you can see that clearly on the Breakfast, Lunch, and Diner’s figures where I was consistently able to complete my meals on the right proportions. 
![results-breakfas-lunch-diner-1](https://github.com/huambra/Personal-Fitness-Dashboard/blob/master/Visualizations/results-breakfas-lunch-diner-1.jpg)

You can also see a similar pattern in the Exercise, Alcohol, and Parties figures, where I was consistent in doing exercise and giving proper recovery to my body, as well as avoiding too much alcohol and excessive parties that could result in fewer hours of sleep. 
![results-exercise-alcohol-parties-1](https://github.com/huambra/Personal-Fitness-Dashboard/blob/master/Visualizations/results-exercise-alcohol-parties-1.jpg)

The interesting patterns, however, start to appear when I analyzed the effect each habit (Food, Exercise, Alcohol, Parties) had on my weight over time (by day). I found that my eating habits have a tremendous effect on my weight as we can see in the figure, where there are weight drops after a day of not completing all my meals:
![restuls-food-on-weight-1](https://github.com/huambra/Personal-Fitness-Dashboard/blob/master/Visualizations/restuls-food-on-weight-1.jpg)

Exercise also plays an important part in gaining weight, as we can see in the figure, I tend to gain weight when I was the most active and stop gaining weight when I wasn’t properly moving.
![restuls-exercise-on-weight-1](https://github.com/huambra/Personal-Fitness-Dashboard/blob/master/Visualizations/restuls-exercise-on-weight-1.jpg)

Alcohol consumption was able to have a direct impact on my weight practically overnight. As we can see in the figure, the biggest weight drop was due to a night of excessive alcohol.
![restuls-alcohol-on-weight-1](https://github.com/huambra/Personal-Fitness-Dashboard/blob/master/Visualizations/restuls-alcohol-on-weight-1.jpg)

Parties also influenced my weight as they determined my hours of quality sleep. Sometimes parties relate to alcohol consumption, so we can see that a full night of party will most likely be accompanied by alcohol. The combination of these 2 had by far the worst effects on my body, and affected other habits, as the next day I wouldn’t want to eat all my meals or exercise.  We can clearly see this in the figure: 
![restuls-parties-on-weight-1](https://github.com/huambra/Personal-Fitness-Dashboard/blob/master/Visualizations/restuls-parties-on-weight-1.jpg)

## Conclutions
In conclusion, according to my findings, the best way to have a good relationship with your body is to have a proper balance between your habits. A slice change in one can have a cascade effect like when a full night of party can result in excessive alcohol consumption, which also can result in poor eating habits the following days. It truly, all comes down to having healthy eating habits, moving your body constantly with proper rest, and having a good relationship with your social life in terms of what you consume and how many hours of quality sleep you are getting. If you have all four, then you are well on your way to having, not only a healthy body but also a healthy life. 