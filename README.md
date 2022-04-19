# Walt Disney World Strategy
**Project** - Compiling, cleaning, analyzing, and predicting wait times for Walt Disney World attractions.

**Data source** - The wait time data spanning from January 2016 to December 2021 for thirteen attractions at the four WDW parks, courtesy of [TouringPlans.com](https://touringplans.com/blog/disney-world-wait-times-available-for-data-science-and-machine-learning/) (themselves a major player in the field of theme park data science).

**Scenario** - We are a young vacation planning company focused primarily on helping families plan their vacations at the major theme parks of the United States. Naturally, this includes the Walt Disney World Resort, the major destination in Orlando, Florida. Our infrastructure is still in its early stages, but we hope to use wait time data taken from a variety of park APIs, along with other information (like operational data and weather/temperature), to give customers data-driven recommendations on how to plan their visit.

One of our first clients is a couple looking to visit the WDW resort with their two teenaged children. The family is looking to make memories before the kids head off to college - while they would like to experience as many of the park offerings as possible, they have identified fourteen rides throughout the four parks as their "top must-dos":
- Seven Dwarfs Mine Train, Pirates of the Caribbean, and Splash Mountain in _Magic Kingdom_
- Soarin' and Spaceship Earth in _Epcot_
- Alien Swirling Saucers, Rock'n'Rollercoaster, Slinky Dog Dash, and Toy Story Midway Mania in _Hollywood Studios_
- Expedition Everest, Avatar Flight of Passage, Kilimanjaro Safaris, and Navi River Journey in _Animal Kingdom_

Their schedules are flexible and their PTO is generous enough that they can visit at whatever time of year we recommend, but they want assurances that they will be able to do everything they want to do when they get there. They are reluctant to rely on paid line-skipping services like Disney's [Lightning Lane](https://disneyworld.disney.go.com/genie/lightning-lane/) and would rather optimize their time to wait in the standby line for rides.

**[Data cleaning](https://github.com/sara-fisher/wdw-waits/blob/main/WDW%20-%20Data%20Cleaning.ipynb)** - Removing observations with downtimes and major outliers, combining the individual datasets, exporting to CSV.

**[Analysis](https://github.com/sara-fisher/wdw-waits/blob/main/WDW%20-%20Data%20Viz%20and%20Analysis.ipynb)** - Analyzing general trends by park and ride over year, month, weekday, and hour to then pinpoint the ideal four-day visit in 2022, the ideal park to visit each day, and what rides to prioritize first thing.

**[Dashboard](https://public.tableau.com/app/profile/sara5821/viz/WaltDisneyWorldWaitTimes2015-2021/Dashboard1)** - We've implemented an early dashboard based on our historical data for customers to check and interact with for further reference.

**What's next?** - We hope to use park operations and weather data (also courtesy of TouringPlans.com) and - after some feature engineering - test multiple regression models to actually predict wait times for our customers' visits.
