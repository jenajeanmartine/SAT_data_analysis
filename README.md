# ReadME Project 1  |  Jena Brentano


## Problem Statement
	The College Board, the non-profit which creates and administers the SAT, wants insights on how they might increase participation in the test among US students. The data available pertain to the SAT and also the ACT which is a competing assessment not administered by the College Board. 
    
---

## Description of Data
	Available are four tables of data that outline the test scores and participation rates by state (plus Washington DC) of the SAT and the ACT for the years 2017 and 2018. Each of the four datasets have about 51 rows, and were originally obtained. Except for pertaining to the ACT 2017, the scores are broken down by subject, as well as given as totals/composites. Combined into one table, the data is as outlined in the data dictionary below. 5.	https://blog.collegevine.com/here-are-the-average-sat-scores-by-state/
https://blog.prepscholar.com/act-scores-by-state-averages-highs-and-lows
    
### Data Dictionary

|Feature|Type|Dataset|Description|
|---|---|---|---|
|state|object|act_2017 & sat_2017|Includes all U.S. states and Washington D.C.|
|participation_act17|float|act_2017|Percentage in decimal form of student participation in the ACT test.| 
|english_act17|float|act_2017|Average english score for the ACT (by state).| 
|math_act17|float|act_2017|Average math score for the ACT (by state).| 
|reading_act17|float|act_2017|Average reading score for the ACT (by state).| 
|science_act17|float|act_2017|Average science score for the ACT (by state).| 
|composite_act17|float|act_2017|Average total score (all other subtests added together).| 
|participation_sat17|float|sat_2017|Percentage in decimal form of student participation in the SAT test.| 
|language_sat17|int|sat_2017|Average evidence-based reading and writing score for the SAT (by state).| 
|math_sat17|int|sat_2017|Average math score for the SAT (by state).| 
|total_sat17|int|sat_2017|Average total score for the SAT (by state).| 

## Primary Findings/Conclusions:

-There's an inverse relationship between participation rates and test scores. Makes sense, many states make the tests madatory, resulting in a higher participation rate, reducing the opt-in bias that is probably responsible for high scores in states with low participation.

-There is a large spread in participation rates for both tests, with some states participating 100% and others below 10%, and some states had a huge change in participation rate due to policy and contracts between states and the College Board

-States tend to be polarized on which test they participate in. It makes sense to focus on getting 'market share' in states that have not yet chosen either the ACT or SAT. California is a great example of a potential high impact focus for increasing test takers. CA had an increase in SAT participation from 2017-2018 to 60%, and because it has such a huge population, there's a lot to gain from increasing statewide participation. Because CA is a diverse and left leaning state, and because it's the right thing to do, the College board should focus on fairness, access and inclusion for a culturally, linguistically and economically diverse population.

### Outside Research (repeated from jupyter notebook of code)
California, Oregon, Alaska don't have exceedingly strong participation in either test (broadly around 50% for each), but they do all have traction for SAT participation (~40-60% participation) and an increase in SAT participation (by 5-7%) for 2017-2018. This makes them sensible targets of focus for states in which we might try to increase percentage participation. California, being the largest of these three states by far, could have the greatest return on investment. Because California is a left leaning and very diverse state, the College Board should keep up a strong focus on equity and inclusion, evolving the test to be less biased toward students of a certain background, and fair access and incentives for underserved communities.



Citations
https://wallethub.com/edu/most-least-diverse-states-in-america/38262/
https://www.cde.ca.gov/
https://blog.prepscholar.com/act-scores-by-state-averages-highs-and-lows
https://blog.collegevine.com/here-are-the-average-sat-scores-by-state/
https://magoosh.com/hs/sat/sat-scores/2018/average-sat-scores-by-state-how-does-your-state-stack-up/
https://blog.prepscholar.com/history-of-the-sat-its-many-failures-and-controversies
