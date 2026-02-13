Dilara Ozdemir

---

## 2/17/2026

Goals for this week:

- [ ] Exploratory data analysis
- [ ] Building/training data
      - Regression 

## 2/9/2026

Goals for this week:

- [X] Combine Weather Data into one data
- [X] Clean the data - take out the unnecessary variables like the Station ID


I acquired the Weather data by downloading them separately through Windows PowerShell and then combined them using R.
I downloaded the combined data set to easily find it next time. 
I started cleaning it out but it has some NA variebles but I will double check and continue next week. 

---

## 2/2/2026

Goals for this week:

- [X] Get access to each block and walkability score
- [X] Familiarize myself with the data set
- [X] Make a general plan for the project and divide it into weeks

### Last Week's Goals:

- [x] Find a topic  
- [x] Find data set

#### Reflections:
The app I downloaded to open the .gdp file did not work but I managed to open the data in R at the end. 
Here are what each of the main variables in the data set mean:
Intersection density: D3b 
Proximity to transit stops (meters from population center to nearest transit stop): D4a 
Employment Mix: D2b_E8MixA
Employment and household mix: D2a_EpHHm

There are a lot of variables where the place name is missing, but there are still coordinates. 
So when I am doing the visuals I am thinking of focusing on creating shape data of the maps. 
The weather data has been divided into separate files by station. I will work with Gemini to download all of them into one.
And focus on temperature, perspiration, rain vs snow, wind speed, and latitude and longitude to help map it to locations
---
