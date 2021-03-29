# GraphQLAPIForTweetsData
A Java spring boot application which uses both REST and GraphQL based APIs running on the same data. REST is used by the existing API services so it can provide a good reference to compare the result against the proposed API. Both the services are operating on the same twitter data collected from Kaggle's "twitter-airline-sentiment" consisting of 14000 tweets consisting of 15 fields each. The experiment is designed to test the efficiency of both the APIs in multiple scenarios as listed below:
1. Retrieving the entire data, all 4800 tweets with all 16 fields.
2. Getting the data for specific fields defined by the user for specific tweets needed by the user.
