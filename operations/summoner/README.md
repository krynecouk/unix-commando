# Operation Summoner

## Objectives

1. create sum of all debts from `/resources/debts.txt`;
2. printed result should be `1950.50$`.

## Solution

```sh
awk 'BEGIN{sum=0} {sum+=$3} END{printf "%.2f$\n", sum}' ./resources/debts.txt
```
