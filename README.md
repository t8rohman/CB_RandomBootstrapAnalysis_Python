# CB_RandomBootstrapAnalysis_Python

Shows you how to do a random assignment, bootstrap, and data analysis for consumer behavior experiment data. I replicated the method and code from the book  **Behavioral Data Analysis with R and Python (2021) written by Florent Buisson**. But, I did several modifications to make it easier and more replicatable to do this kind of analysis in the future

For the data, this is the business case of a fictional company, AirCnC. The management of AirCnC has determined that adding a "1-click booking" button will significantly increase the company's booking rate. In this business case, there will be 3 steps in conducting the experiment:

1. Randomization the assignment of the treatment and control to the user ID
2. Determining the sample size of the experiment

And let's say, if we already conducted the experiment and have the data, the last one is:

3. Analyzing the result using traditional regression and bootstrap simulation
