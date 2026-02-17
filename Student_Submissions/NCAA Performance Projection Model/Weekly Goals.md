## 1/12/2026

Goals for this week:

[x] Clone old tfrrs scraper repo  
[ ] Adapt the harverser.py file to scrape athletic.net meets.
[ ] Adapt/create new processor.py files to process those meets.
[ ] Create a new database schema, with all this, and future changes in mind (athletic.live, training data, milesplit, pro-racing)

### Last Week's Goals:

[x] Upload  
[x] Locate the web hooks for athletic.net
[x] Create a branch on main for the antigravity code
[x] Find the hidden web API for athletic.net main site

#### Reflections:

I have the antigravity code 'working' but there are a lot of issues with the implementation.
It is extremely slow, upwards of 2mins per meet, far too slow for use, would take weeks to scrape 40000+ meets (for just one year)
I theorize this is because it is using playwright, an automated browser, and opening a new instance for every single meet.
So rather than 'fix' these fundamental design issues, it is easier to just scrap it and take what I can out to use. 
I will use the existing (working) tfrrs scraper as a boilerplate.
Also, schema design needs rework.