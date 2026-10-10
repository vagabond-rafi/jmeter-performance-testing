# OctoPerf PetStore — JMeter Performance Test

Load and performance testing performed using Apache JMeter on the OctoPerf PetStore web application.

## Application Under Test

**Website:** https://petstore.octoperf.com/actions/Catalog.action

## Test Overview

| Item           | Details                            |
| -------------- | ---------------------------------- |
| Test Type      | Load Testing / Performance Testing |
| Testing Tool   | Apache JMeter                      |
| Protocol       | HTTP                               |
| Total Requests | 2,000                              |
| Test Verdict   | Pass with Performance Concerns     |

## Test Results

| Metric                |                 Result |
| --------------------- | ---------------------: |
| Average Response Time |    3,440 ms (3.44 sec) |
| Minimum Response Time |                 578 ms |
| Maximum Response Time |  17,586 ms (17.59 sec) |
| Standard Deviation    | 3,241.41 ms (3.24 sec) |
| Error Rate            |                0.2655% |
| Throughput            |    0.2326 requests/sec |
| Received Data Rate    |          4.4564 KB/sec |
| Sent Data Rate        |         0.03021 KB/sec |
| Average Response Size |               19.62 KB |

## Key Findings

* Processed 2,000 HTTP samples during the test.
* Average response time was 3.44 seconds.
* Maximum response time reached 17.59 seconds.
* The error rate was 0.2655%.
* Throughput was approximately 0.2326 requests/second.
* Response times showed substantial variability.

## Performance Assessment

**Overall Status: PASS WITH PERFORMANCE CONCERNS**

The test processed the supplied request volume, but the response-time variability, maximum latency, and non-zero error rate require further investigation. The low measured throughput should also be interpreted cautiously because concurrency, ramp-up, test duration, and workload configuration were not provided.

## Recommended Next Steps

* Investigate failed HTTP requests and their status codes.
* Repeat testing at multiple concurrency levels.
* Record ramp-up period and test duration.
* Capture P95 and P99 response-time percentiles.
* Monitor server and database resources, where accessible.

## Full Report

[View the Complete JMeter Performance Test Report](./JMeter_Load_Test_Report_OctoPerf_PetStore_2000_Requests%281%29.docx)
