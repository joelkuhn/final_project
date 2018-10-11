## Final Project, Part 1: *Proposal*

#### Overview
An ultra-marathon is defined as any foot race with a distance greater than 26.2 miles. To an individual not familiar with the ultrarunning scene this may sound insane and at the most something someone may attempt to complete as a once in a lifetime accomplishment. However, it’s rare that someone will run only one ultra in their life. In fact, ultra-running is often considered a lifestyle that involves regularly running races of 50 kilometers, 50 miles, or even 100 miles. Unlike many marathons that are usually completed on roads with minimal variation in the terrain, ultras are more often likely to take part on trails where mountainous conditions with dramatic elevation changes (10’s of thousands of feet) are to be expected. This means that making predictions of an individual's performance in an upcoming race is much more complex than the arguably well known methods and calculators that are used for road marathons.

Currently the best methods used for predicting ones performance in an upcoming race is through a race signup website (much like using Ticketmaster.com for concert tickets). Most ultra trails races use this page to organize and collect registration fees. All results are subsequently logged. After each race, a participant is given a rating that is simply their finish time as a percentage of the winners finish time. Their current rank is an average percentage of all of their logged races, and predictions are calculated as the winning time over the past 4 years divided by this average rank. 

#### Proposal
I propose to use machine learning techniques in order to more reliably predict how individuals will perform in specific races.
If possible, a secondary goal would be to generalize these results into different classes of races. Potentially finding the best metrics to make these classifications (i.e. race distance, average race altitude, average elevation gain/loss, avg temperatures, etc.)

I will get data from two sources:
- The first is the previously mentioned race registration website (ultrasignup.com). This information is all public and accessible.
- The second is the fitness social media website Strava.com. This is an online location for athletes to log their training runs and races. It uses GPS data to log this information. So location and time points are accessible for each available run.

I will consider this project successful if the methods I use more reliably predict an individual's time for a race than the current methods.

#### Risks or limitations
- One potential problem I may run into is with my own skill limitations with organizing the data. Ultrasignup.com does not appear to have any API that will be effective so this collections will be done through webscraping techniques.
- Another issue is going to be in missing data. While many athletes have public profiles with all of there running data available on strava.com, this is not always the case. Some may also not post all of their key workouts/runs. Dealing with this missing data appropriately could be a challenge.
