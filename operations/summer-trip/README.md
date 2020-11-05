# Operation Summer Trip

## Objectives

1. `cd` to the folder containg the file `italy`;

## Solution

```sh
cd $(find . -name italy 2> /dev/null | xargs dirname)
```
