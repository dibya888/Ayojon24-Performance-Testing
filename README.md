\# Ayojon24 Website Performance Testing



Performance and load testing of \[Ayojon24.com](https://ayojon24.com/) using Apache JMeter.



\## Live Test Report



\*\*\[View Interactive HTML Dashboard](https://dibya888.github.io/Ayojon24-Performance-Testing/LoadTest\_Report/html-dashboard/)\*\*



\## Test Overview



\- \*\*Tool:\*\* Apache JMeter 5.6.3

\- \*\*Test Type:\*\* Load Testing

\- \*\*Virtual Users:\*\* 5

\- \*\*Test Duration:\*\* 5 minutes

\- \*\*Ramp-up Period:\*\* 30 seconds

\- \*\*Think Time:\*\* 2 seconds

\- \*\*HTTP Method:\*\* GET

\- \*\*Assertions:\*\* HTTP response code 200



\## Test Results



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



\## Scope



The test plan sends GET requests to the homepage and eight category pages. Response code assertions verify that each request returns HTTP 200.



\## Project Files



\- `Ayojon24\_Load\_Test.jmx` — JMeter test plan

\- `LoadTest\_Report/loadtest-results.jtl` — Raw test results

\- `LoadTest\_Report/html-dashboard/` — Generated HTML dashboard and supporting assets



\## Important Notes



This test represents a small, controlled load of five virtual users. The results do not establish the website's maximum capacity or guarantee performance under heavy traffic. Response times can vary with network conditions, server load, caching, and the test environment.



\*\*Disclaimer:\*\* This is an independent testing project and is not an official report commissioned or endorsed by Ayojon24.

