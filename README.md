# Time-Series-

# Resampling
Resampling basically means representing the data with a different frequency. 
Assume we have a temperature sensor which takes measurements every minute. If we do not need to have a minute-level precision, we can take the average of 60 minute measurements in an hour and show the changes in the temperature hourly. This is down-sampling which means converting to a lower frequency.

Resampling can be done using resample() or asfreq() functions.

Resample: Aggregates data based on specified frequency and aggregation function.

Link : https://towardsdatascience.com/resample-function-of-pandas-79b17ec82a78


