We have two datetime features and want to calculate the time between them for each observation, Subtract the two date features using pandas Often we will want to remove the days output and keep only the numerical value
There are times when the feature we want is the change (delta) between two points in time. For
example, we might have the dates a customer checks in and checks out of a hotel, but the feature we
want is the duration of his stay. pandas makes this calculation easy using the TimeDelta data type
