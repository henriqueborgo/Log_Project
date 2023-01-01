
# Log Project

Project to erase unwanted characters from the LOG alert document




## Authors

- [@henriqueborgo](https://www.github.com/henriqueborgo)
- [@vborgo](https://www.github.com/vborgo)

## Introduction

This project was concepted to help my brother on a job task. The Log Alert document is a .txt file generated with hundreds of thousants of lines. The problem to solve here, is the variation of information in each line, that resulted in a harder work to erase the unwanted parts line by line with memory eficciency.

The execution will result:

* Raw log document example (.txt file)

[10:21:58.605084 66543.400337] [31m09:21:58  [ERR] integ_get_station_status (wifi_ctrl.c:485) - integ_get_station_status not implemented[0m
[10:21:58.694364 0.080399] [36m09:21:58  [INF] battery_event_stats_changed (eagle.c:1907) - Charger connected[0m

* Cleaned log document (.txt file)

[ERR] integ_get_station_status (wifi_ctrl.c:485) - integ_get_station_status not implemented
[INF] battery_event_stats_changed (eagle.c:1907) - Charger connected









## Summary of Tech Stack

This project was built using **Python**. The work was elaborated in Google colabority IDE.

To run this project import libraries:

- Pandas
- Numpy


## Running Locally

Running the Log project in yout local dev envirment is very easy. Be sure to have Python installed, then follow the directions bellow.

1. Clone the source code

2. Copy the log .txt file to the same folder as the project and namet it "log_teste.txt"

3. Run. The Log_Project will generate a .txt file called 'output.txt' as result
