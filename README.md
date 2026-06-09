# CI/CD Pipeline Failure Troubleshooting

## Project Overview

This project demonstrates how to identify, troubleshoot, and fix a failing CI/CD pipeline using GitHub Actions.

## What I Did

* Created a Python application.
* Configured a GitHub Actions workflow.
* Triggered a CI/CD pipeline through a GitHub push.
* Analyzed pipeline execution logs.
* Identified the root cause of the failure.
* Fixed the workflow configuration.
* Verified successful pipeline execution.

## Problem

The pipeline failed because the workflow attempted to execute a Python file that did not exist in the repository.

## Root Cause

The workflow contained:

python missing_file.py

The file `missing_file.py` was not present in the project.

## Solution

Updated the workflow to run the correct application file:

python app.py

## Tools Used

* Git
* GitHub
* GitHub Actions
* Python
* Linux (WSL)

## Skills Demonstrated

* CI/CD Troubleshooting
* GitHub Actions
* Log Analysis
* Root Cause Analysis
* Pipeline Debugging
* Version Control with Git

## Outcome

Successfully identified and fixed a CI/CD pipeline failure, resulting in a successful GitHub Actions workflow execution.
