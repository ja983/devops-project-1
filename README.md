# DevOps Internship — Project 1: Linux & Command Line Basics

## Overview

This project marks the foundation phase of my DevOps internship at DecodeLabs. Before automating cloud pipelines, the goal was to master the core language of servers: the Linux terminal. This repo documents the "Intern Mission: Web App Setup" exercise — building, verifying, and managing a small file structure using pure command-line operations.

## What This Demonstrates

- File and directory operations (`mkdir`, `touch`, `cp`, `mv`, `rm`)
- Navigation and directory structure awareness (`pwd`, `cd`, `ls -R`)
- Viewing and monitoring files (`cat`, `echo` redirection, `tail -f`)
- Understanding file permissions (`ls -l`, `chmod`, `chown`)
- Safe deletion practices (`rm -i` vs `rm -rf`)

## Project Structure

```
app/
├── config.conf       # Placeholder config file
└── logs/
    └── server.bak    # Renamed from server.log (backup step)
```

## Mission Steps

| # | Step | Command |
|---|------|---------|
| 1 | Scaffold the directory | `mkdir -p app/logs` |
| 2 | Create the config file | `touch app/config.conf` |
| 3 | Write to the log file | `echo "Started" > app/logs/server.log` |
| 4 | Verify the structure | `pwd && ls -R app` |
| 5 | Back up the log | `mv app/logs/server.log app/logs/server.bak` |
| 6 | Audit permissions | `ls -l app/config.conf` |

## How to Reproduce

mkdir -p app/logs
touch app/config.conf
echo "Started" > app/logs/server.log
pwd && ls -R app
mv app/logs/server.log app/logs/server.bak
ls -l app/config.conf


## Tools Used

- Git Bash (Windows)
- VS Code
- Git / GitHub

This completes Project 1, which unlocks the next project in the DecodeLabs DevOps track.
