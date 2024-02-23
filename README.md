This dataset contains information about different accounts over multiple time steps, with various features recorded at each time step and an event occurring or not at each step. Following is the format of dataset.

Account | Time Step | Feature 1 | Feature 2 | Feature 3 | Event
-----------------------------------------------------------------
1       | 1         | 0.1       | 0.2       | 0.3       | 0
1       | 2         | 0.2       | 0.3       | 0.4       | 0
1       | 3         | 0.3       | 0.4       | 0.5       | 1
1       | 4         | 0.4       | 0.5       | 0.6       | 0
1       | 5         | 0.5       | 0.6       | 0.7       | 0
2       | 1         | 0.2       | 0.3       | 0.4       | 0
2       | 2         | 0.3       | 0.4       | 0.5       | 0
2       | 3         | 0.4       | 0.5       | 0.6       | 1
2       | 4         | 0.5       | 0.6       | 0.7       | 0
2       | 5         | 0.6       | 0.7       | 0.8       | 0
3       | 1         | 0.3       | 0.4       | 0.5       | 0
3       | 2         | 0.4       | 0.5       | 0.6       | 0
3       | 3         | 0.5       | 0.6       | 0.7       | 0
3       | 4         | 0.6       | 0.7       | 0.8       | 1
3       | 5         | 0.7       | 0.8       | 0.9       | 0

We randomly generated data for 25000 accounts and timeseries length of each account is 36 time step. Based on historical data i want to create a model to identify if event can be 1 in next time step.
