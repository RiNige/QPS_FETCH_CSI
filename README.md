# About QPS_Fetch

This tool allows you to check and download the latest QPS Award Sheet using the public API endpoint released by DPO.

# How to use

## Pre-requisite
To successfully run the executables, make sure which OS you are using and download the corresponding version:
1. qps_fetch (for mac & linux users)
2. qps_fetch_windows (for windos users)

## Download the latest information into a CSV file
To fetch the latest award information and save it into a local CSV file, run
```bash
./qps_fetch
```

## Filter out non-Chinasoft projects
This function would filter out QPS projects not awarded by Chinasoft and print the output into CSV file
```bash
./qps_fetch -f
```

## Print latest available sheets in terminal
This function checks the available version within the current year and save a output into a json file
```bash
./qps_fetch -l
```