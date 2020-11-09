# Operation No Time To Sha-Bang

## Objectives

1. create shell function that takes name and prints 'Hello, `<name>`!' without any intermediate shell script files;

## Solution

```sh
hello() { echo "Hello, ${1}!"; } && hello "Mr. Bond"
```
