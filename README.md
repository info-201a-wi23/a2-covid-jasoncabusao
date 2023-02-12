# A2: U.S. COVID Trends

## Overview
In many ways, we have come to understand the gravity and trends in the COVID-19 pandemic through data. Regardless of media source, people are consuming more epidemiological information than ever, primarily through reported figures, charts, and maps.

This assignment is your opportunity to work directly with the same data used by the [New York Times](https://github.com/nytimes/covid-19-data/). While the analysis is guided through a series of questions, it is your opportunity to use programming skills to ask more detailed questions about the pandemic.

## Getting Started
You should start this assignment by opening up the `analysis.R` script. The script will guide you through an initial analysis of the data.

* **Coding prompts.** Complete the coding prompts in `analysis.R`.

* **Reflection prompts.** Throughout `analysis.R`, there are prompts labeled `"Reflection"`. Please write at least 1-3 sentences for each of these prompts below in this `README.md` file. As appropriate, provide evidence, give justification for your opinions, or genuinely reflect on your views. Please strive for concise, clear, and interesting writing.

## Reflection 1
Before actually calculating the total number of COVID cases and deaths, record your guesses for the following questions.

Guess: How many total COVID cases do you think there have been in the U.S.?
* I think there have been around 90-100 million COVID cases in the U.S.

Guess: How many total COVID-related deaths do you think there have been in the U.S.?
* I think there have been 10 million COVID deaths in the U.S.

Guess: Which state do you think has the highest number of COVID cases, and which state do you think has the lowest?
* I think New York or California has the highest number of COVID cases. I think states with a lower population may have the lowest number of COVID cases, like Alaska.

## Reflection 2
Did the number of COVID cases and deaths surprise you? Why or why not? What about the states with the highest and lowest number of cases? How did your guesses line up with the actual results? Answer in at least 1-3 sentences
* No, the total number of COVID cases didn't surprise me. The total number of U.S. cases, about 102 milion, was around my prediction of 90-100 million. However, the total number of deaths, about 1 million, did surprise me; it was way less than my prediction of 10 million. My prediction of California having the most COVID cases was correct, whereas, my prediction of Alaska being the state with the lowest cases was wrong. The American Somoa has the lowest recent number of COVID cases

## Reflection 3
Which county has the highest number of cases in the state of Washington, and does it surprise you? Why or why not? (You may need to google this county to learn about it) Answer at least in 1-3 sentences
* The county with the highest number of cases in Washington is King County. This doesn't surprise me since Seattle resides in King County, and Seattle is the most populous city in Washington.

## Reflection 4
Why are there so many observations (counties) in the variable `lowest_deaths_in_each_state`? That is, wouldn't you expect the number to be around 50? Why is the number greater than 50? Answer in at least 1-3 sentences
* The reason for the multitude of counties with the lowest deaths in each state is because many counties had the same number of deaths. Because not many folks died from covid compared to the number of cases, there won't be much variability between the number of deaths between counties.  

## Reflection 5
What do you think about the number and scale of the inconsistencies in the data? Does the fact that there are inconsistencies mean that people should not use this data? Why or why not? Answer in at least 1-3 sentences
* I think the number of inconsistencies between county and national data is rather small in comparison to the overall number observed – 27 out of 844 days, 97% accuracy. With the huge task of collecting new data everyday and having every single one of it be accurate is hard and too much to ask for. I think people should still use this because the data is still relatively accurate and a slight miscalculation of a few hundred cases won't skew your perception of around 100 million cases. 

## Reflection 6
Why were you interested in this particular question? Were you able to answer your question with code? What did you learn? Answer in at least 1-3 sentences
* I was interested in this question because we determined what state had the highest death to cases ratio but not the lowest death to cases ratio. I was able to answer my question with code. The Northern Mariana Islands had the lowest death to cases ratio out of all states listed, with a ratio of 0.003060844.

## Reflection 7
What, if anything, made you curious about this COVID analysis? What, if anything, surprised you? What might you do the same or differently on your next data wrangling project? Answer in at least 1-3 sentences
* Something that made me curious about this COVID analysis is why the data for counties stopped on 5-13-2022. Something that surprised me was the state with the highest death to cases ratio being Pennsylvania. Something I might do differently for my next data wrangling project is start early on it and work on a piece of of it everyday until I finish.