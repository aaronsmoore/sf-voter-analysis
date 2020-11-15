# sf-voter-analysis
Analysis of SF voter data

Analysis of SF voter data using EDA and visualizations. Mainly pandas and seaborn. Here's the tl;dr:

In this notebook, we'll be taking a look at some voter data from the 2020 election and comparing it to historical data. The focus will be on creating a reusable pipeline to analyze election results.

tl;dr:

Analysis of the 2020 SF Election

Summary:

Candidate 2/B won a total of 31 precincts, receiving almost 15 thousand votes in the 11th Preliminary Report of RCV tabulation. From this analysis, the following insights were gleaned:

    In 2016 and 2020, Candidate 2/B won precincts 24, 12, 9, 19, 53, 41, 22, 34, 31, 28, 36, 11, 13, 8, 35, 33, 25,26, 18, 16, 3, 27, 32, 2 both times.
    In 2016 and 2020, Candidate 2/B lost precincts 43, 4, 45, 47, 48, 46, 49 both times.
    Candidate 2/B won 2 additional precincts in 2020 (total went from 29 to 31)
    In Precincts 25 and 11, Candidate 2/B increased their vote count from 2016 to 2020 by 208 and 201 respectively, the highest of all the precinct totals.
    Candidate 2/B won precincts 6, 7, 15, 23, 42, 44, 52 in 2020. Precincts that the candidate lost in 2016.

Tools/Packages Used:

Nothing special, but we developed some new functions specific to analyzing voter/election data. All are reusable and a part of the pipeline.
