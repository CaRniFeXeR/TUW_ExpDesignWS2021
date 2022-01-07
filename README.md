# TUW_ExpDesignWS2021

The Unfairness of Popularity Bias in Music Recommendation:A Reproducibility Study
https://arxiv.org/pdf/1907.13286.pdf
Topic: bias of recommender systems against unpopular items
Reproducing https://arxiv.org/pdf/1907.13286.pdf but with music data instead of movie data
e define the popularity of an artist as the ratio of users who
ave listened to this artist
	
Possible problems
- How did the extracted the 3000 users?
    - 1000 with lowest mainstreaminess scores
    - 1000 with meainstreminess scorue around the median
    - 1000 with highest mainstreaminess scores
    - Possible problems? --> listing history size
        - -->  users with a smaller profile size tend to listen to more popular
        Artists
    - ideas
        - warum nciht random gesamplet?
        - default parameter der recommender?
    - Presentation
        - 4 minuten
        - 5 slides
        - Content
            - Short explaination of the paper
            - Explain WHAT we want to reproduce
            - Explain WHY we reproduce something

### Notes regarding versions:

The original paper was submitted on the 10th of December 2019 (https://arxiv.org/abs/1912.04696).
All versions of the required libraries were chosen to correspond to the latest stable version at this date.
As python 3.8.0 was the latest major python release by the time the paper was submitted (https://www.python.org/downloads/) this version was chosen