# Operation Wolf

## Objectives

1. create file `/resources/X` with modification time 1.1.2012;
2. create file `/resources/Y` with current modification time;
3. clean folder `/resources` from files older than 10 days;

## Solution

```sh
touch -d 20120101 resources/X && \
touch resources/Y && \
find resources/* -mtime +10 | xargs rm
```
