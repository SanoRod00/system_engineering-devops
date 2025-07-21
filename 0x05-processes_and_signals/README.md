# 0x05. Processes and Signals

This directory contains Bash scripts that demonstrate various tasks related to processes and signals in a Unix-like operating system. Each script is part of the **System Engineering & DevOps** curriculum and follows specific requirements for scripting style and execution.

## Learning Objectives

- Understand what a PID is and how to find it
- Learn about process states and how to list running processes
- Understand the difference between foreground and background jobs
- Learn how to send signals to processes and terminate them
- Explore zombie processes and how to create/handle them

## File Descriptions

| File Name                 | Description                                                                 |
|--------------------------|-----------------------------------------------------------------------------|
| `0-what-is-my-pid`       | Prints the PID (process ID) of the current shell                            |
| `1-list_your_processes`  | Displays a list of currently running processes                              |
| `2-show_your_bash_pid`   | Shows the PID of the Bash shell and its child processes                     |
| `3-show_your_bash_pid`   | Displays the PID and parent PID using various methods                       |
| `4-to_infinity_and_beyond` | Starts a process that runs indefinitely                                   |
| `5-dont_stop_me_now`     | Sends a SIGTERM signal to a process running from script 4                   |
| `6-stop_me_if_you_can`   | Creates a process that cannot be terminated using SIGINT                    |
| `7-highlander`           | Kills a running process and ensures only one instance is running            |
| `8-beheaded_process`     | Demonstrates how to kill a process using `kill -9`                          |

> ⚠️ All scripts start with `#!/usr/bin/env bash` and include a comment describing what the script does.

## Usage

To run any script:
```bash
./[script_name]
