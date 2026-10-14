# Ayojon24 Website Performance Testing

Performance and load testing of [Ayojon24.com](https://ayojon24.com/) using Apache JMeter 5.6.3.

## Live Test Report

**[View Interactive HTML Dashboard](https://dibya888.github.io/Ayojon24-Performance-Testing/LoadTest_Report/html-dashboard/)**

## Test Overview

- **Test Type:** Load Testing
- **Virtual Users:** 5
- **Test Duration:** 5 minutes
- **Ramp-up Period:** 30 seconds
- **Think Time:** 2 seconds
- **HTTP Method:** GET
- **Assertions:** HTTP response code 200

## Test Results

| Metric | Result |
|---|---:|
| Total Requests | 452 |
| Failed Requests | 0 |
| Error Rate | 0% |
| Average Response Time | 1,178.71 ms |
| Median Response Time | 656 ms |
| 90th Percentile | 916 ms |
| 95th Percentile | 1,947.5 ms |
| 99th Percentile | 2,278.7 ms |
| Maximum Response Time | 7,531 ms |
| Throughput | 1.51 requests/sec |

## Test Scope

The test plan covers the homepage and eight category pages. HTTP response code assertions verify that requests return status 200.

## Project Files

- `Ayojon24_Load_Test.jmx` — JMeter test plan
- `LoadTest_Report/loadtest-results.jtl` — Raw test results
- `LoadTest_Report/html-dashboard/` — HTML dashboard and supporting assets

## Limitations

This test used only five virtual users. It does not establish the website's maximum capacity or guarantee performance under heavy traffic. Results may vary with network conditions, caching, and server load.

## Disclaimer

This is an independent testing project and is not an official report commissioned or endorsed by Ayojon24.
