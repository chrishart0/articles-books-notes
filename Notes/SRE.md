# SRE



## Definitions

#### White-box monitoring

Monitoring based off of internal metrics, not exposed to the outside world. Examples: text logs, server metrics, performance logs, utilization metrics. 

#### Black-box monitoring

Testing of externally facing components.

## Error Budget

..... errors per quarter.

## 4 Golden Signals

### Latency

Time it takes to serve a request. 

* It is important to differentiate between latency for successful and failed requests. 
  * If an internal call times out and then your service returns a 500 this will have a vastly different latency than a successful call, throwing off your metrics. 

### Traffic

A measure of system utilization

### Errors

A measure of unsuccessful calls

* Could be 500s, 200s with bad data
    * Bad data may only be able to be detected by integration or e2e tests
* Could be responses with too much latency
    * Example: Anything with more than 1 second latency is considered an error

### Saturation

A measure of how close to max utilization is your system, focus on the resources which are most constrained. 

Examples: 
    * For a web server you may focus on CPU and Memory utilization
    * For a file server you may focus on I/O and disk utilization as well as memory

#### Degradation

Many systems will degrade in performance before reaching 100% utilization, pay attention to this and know where that point is for your system.

#### Prediction 

Saturation is also concerned with the ability to predict when limits will be reached.

Examples:
* At the current growth rate of memory utilization, the web server will start to experience performance degradation in 4 hours and reach 100% memory utilization in 8 hours
* The DB server's HDD will reach 100% utilization in approximately 10 days


## Note on statistics

Be carful not to just monitor averages(mean). While your average may be healthy, you could be missing some number of outliers which are not. It is important to monitor for both average, 90/99th percentile, and maximum. 