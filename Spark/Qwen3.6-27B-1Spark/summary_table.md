# Qwen3.6-27B-1Spark 性能测试汇总表

数据来源：各并发文件夹下的 `profile_export_aiperf.csv`（Metric 的 avg 值）

| concurrency | Input Sequence Length (tokens) | Output Sequence Length (tokens) | Time to First Token (ms) | Prefill Throughput Per User (tokens/sec/user) | Output Token Throughput Per User (tokens/sec/user) | Request Latency (ms) |
|---|---|---|---|---|---|---|
| 1 | 1000.00 | 1000.00 | 864.10 | 1157.31 | 4.60 | 217955.46 |
| 5 | 1000.00 | 999.76 | 3331.76 | 326.29 | 4.56 | 222586.09 |
| 10 | 1000.00 | 999.88 | 4419.79 | 254.62 | 4.29 | 237170.74 |