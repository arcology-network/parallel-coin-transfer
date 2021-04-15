# parallel-coin-transfer

## 1. Tests

- [Interactive](/doc/parallelized-coin-transfer-interactive.md)
- [Benchmarking](/doc/parallelized-coin-transfer-benchmark.md)

## 2. Using Pre-generated Transactions

Generating large volumn of transactions can be a lengthy process that takes a lot of time. To benchmark the system, we suggest you using the pre-generated transaction files under the test case directories, which contain readily signed transctions in binary format.

## 3. Note

> *Please wait for one script to complete before starting the next one. The best way to tell is by looking at the number of transactions contained in the lastest block. Once the number of transactions in the latest block drops to zero(not rising from zero which shows the system is picking up speed), it shows the system has processed all transactions.*
>