# script to writes out the current user to a log file

#!/bin/bash

## Get the current logged-in user
    logged_in_user=$(whoami)

## Get the current system time
    system_time=$(date)

## Log file path
    log_file="logged-in-user.log"

## Append the logged-in user and system time to the log file
    echo "Logged-in user: $logged_in_user | System time: $system_time" >> "$log_file"
