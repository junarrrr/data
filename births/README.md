# U.S. Births

This folder contains data behind the story [Some People Are Too Superstitious To Have A Baby On Friday The 13th](http://fivethirtyeight.com/features/some-people-are-too-superstitious-to-have-a-baby-on-friday-the-13th/).

There are four files:

`US_births_1994-2003_CDC_NCHS.csv` contains U.S. births data for the years 1994 to 2003, as provided by the Centers for Disease Control and Prevention's National Center for Health Statistics.

`US_births_2000-2014_SSA.csv` contains U.S. births data for the years 2000 to 2014, as provided by the Social Security Administration.

`US_births_2003_CDC_NCHS.csv` contains U.S. births data for the year 2003, as provided by the Centers for Disease Control and Prevention's National Center for Health Statistics. (fork specific)

`US_births_2003_SSA.csv` contains U.S. births data for the year 2003, as provided by the Social Security Administration. (fork specific)

All files have the following structure:

Header | Definition
---|---------
`year` | Year
`month` | Month
`date_of_month` | Day number of the month
`day_of_week` | Day of week, where 1 is Monday and 7 is Sunday
`births` | Number of births
