
You are given a blob of data of approximately 1 minute of signal. The data structure
carries measurements for 8 sensors, each observation consisting of a sample and its timestamp.
The sampling frequency is told to be approximately 41.7 Hz.

1. Look at the data structure and at the values that are stored - Report your interesting 
observations and facts, as well as the questions you may want to ask to the people you work
with regarding the data you are provided.

2. Write a python function that extracts the Training Load for each muscle. The training load
is defined as the area under the curve of the EMG you are given over a slice of time.

3. Discuss how you implemented the function, what are pros and cons, and how the answers you
may have had in 1/ might drive how you would change the implementation if needed.
