# Results Table

| Variant | Proxy first +5s | Simultaneous | Client first +30s |
|---------|----------------|--------------|-------------------|
| Baseline (100%) | 10.6 11.3 12.8 s | 6.1 6.2 s | 57.8 37.3 95.4 49.9 s |
| Modified (50%) | 9.8 11.8 9.25 s | 143.1 5.4 5.0 s | 48.4 100.4 75.0 35.3 119.4 s |
| Modified (Brokers = 3) | 9.6 9.2 9.5 s | 5.5 5.3 4.2 s | 40.1 41.2 37.9 s |
| Modified (ClientOffer Timeout = 10s) | 9.4 9.4 9.3 s | 5.6 4.0 7.3 s | 58.7 59.3 59.0 s |
