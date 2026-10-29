# Cosmetix Glow BD — JMeter Performance Test

Performance and load testing performed using Apache JMeter on the Cosmetix Glow BD web applicati

## Application Under Test

**Website:** https://cosmetix-glow-bd.vercel.app/

## Test Overview

| Item | Details |
|---|---|
| Test Type | Load Testing / Performance Testing |
| Testing Tool | Apache JMeter |
| Protocol | HTTP |
| Total Requests | 1,000 |
| Test Target | HTTP Request |
| Test Verdict | Pass with Performance Concerns |

## Test Results

| Metric | Result |
|---|---:|
| Average Response Time | 6.104 sec |
| Minimum Response Time | 2.472 sec |
| Maximum Response Time | 17.586 sec |
| Standard Deviation | 2.605 sec |
| Error Rate | 0.531% |
| Throughput | 55.28 requests/sec |
| Received Data Rate | 1,813.51 KB/sec |
| Sent Data Rate | 6.75 KB/sec |
| Average Response Size | 33.60 KB |

## Key Findings

- The application successfully processed 1,000 HTTP requests.
- Average response time was 6.104 seconds.
- Maximum response time reached 17.586 seconds.
- The test recorded a 0.531% error rate.
- Throughput reached approximately 55.28 requests/second.
- Response-time variability was relatively high.

## Performance Assessment

**Overall Status: PASS WITH PERFORMANCE CONCERNS**

The application successfully processed the tested workload, but the response-time results indicate potential performance optimization areas.

Further testing is recommended with different concurrency levels, ramp-up patterns, P95/P99 response-time measurements, and server-resource monitoring.

## Full Report

[View the Complete JMeter Performance Test Report](./Cosmetix-Glow-BD-JMeter-Report.docx)
