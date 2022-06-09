# flamegraph-results

Some flamegraphs for different types of traffic:

- UDP_LOW: UDP size = 500, @ 1Kpps, 4Mbps
- UDP_HIGH: UDP size = 500, @ 100Kpps, 400Mbps
- UDP_SMALL: UDP size = 100 @ 500Kpps, 400Mbps
- BURST_UDP: UDP size = 500 @ 100Kpps with 1 second intervals.

Ran on arch 5.16.16-arch1-1, using perf for capturing kernel stack @ 999hz for 65 seconds.
