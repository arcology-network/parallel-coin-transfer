
# Benchmark Token Transfer

The performance observer gives realtime performance information for block height, number of transctions in each block, max TPS and average TPS over 60 seconds.
>Please note the observer only starts to output TPS when the node cluster is actively processing transctions

```shell
$ ./tps.sh
```

![alt text](./images/performance-observer.png)

##  1. Test balance transfer between accounts

Benchmarking system performance with 5 million balance transfer transactions between 5 million user addresses

```shell
$ ./send_simple_transfer_txs.sh
```

![alt text](./images/balance-tranfer.png)


## 2. Troubleshooting

In interactive mode, if you ran the code snippets provided in the documents and got unexpected results, the cause may be complicated. There are a couple of things you can do for a quick fix:

1. Check if the account you used to sign transactions has enough balance to pay the gas by calling *Cli.getBalance(address)*
2. Find another account from *~/accounts.txt* and try again.