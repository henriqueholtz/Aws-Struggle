# Predictive scaling

Predictive scaling uses machine learning to predict capacity requirements based on historical data from CloudWatch. The machine learning algorithm consumes the available historical data and calculates capacity that best fits the historical load pattern, and then continuously learns based on new data to make future forecasts more accurate.

- To manage a workload that exhibits recurring load patterns that are specific to the day of the week or the time of day

Predictive scaling is well suited for situations where you have:

1. Cyclical traffic, such as high use of resources during regular business hours and low use of resources during evenings and weekends
2. Recurring on-and-off workload patterns, such as batch processing, testing, or periodic data analysis
3. Applications that take a long time to initialize, causing a noticeable latency impact on application performance during scale-out events
