#Project Roadmap: Athlete Performance Prediction

##Phase 1: Data Collection - College (Complete)
[x] Scrape college athlete race results (TFRRS)

##Phase 2: Data Collection - High School (Athletic.net)
[ ] Current Focus: Optimization & Ingestion

###Sub goals:

[x] Find webhook to index meet searches from
[ ] Create script to gather list of meet links
[ ] Create script to download formatted race results from a given meet
[ ] Adapt pSQL schema to include athlete age
[ ] Figure out if I NEED age, or if I can get by with just race times?
[ ] Can do Race dates + if on HS team, no team (gap year), then college team (in college now)

####Download race results sub goals:

[ ] Get meet information: Date, name, location, age group
[ ] Find sub hooks for each race
[ ] Find html format for races (get distance and heat) find html column positions for: athlete name, time, position, age/date
[ ] Make sure that I have the date for the races correct, if athlete age is not possible (So I can do time series using the start of college as an anchor?)


####Normalization: 
[ ] Standardize event names and distances to match the college dataset.

##Phase 3: Training Data Acquisition
###Investigate data access methods (API limitations vs. public profile scraping).
[ ] Develop a strategy for matching athlete names/locations to profiles.

[ ] Collect publicly available training logs (mileage, workout types).

##Phase 4: Modeling & Prediction
[ ] Feature Engineering (Qualifying standards, seasonal performance).

[ ] Build prediction model for Indoor, Outdoor, and XC performance.
