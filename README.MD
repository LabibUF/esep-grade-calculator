# ESEP Grade Calculator

## Project Overview
This project is a grade calculator written in Go. It calculates a student's final letter grade using their assignment, exam, and essay scores.

## Requirements
Go version 1.24.4 or newer

## Grading System
The final grade is calculated using these weights:
Assignments: 50%
Exams: 35%
Essays: 15%

## Letter Grade Scale
A: 90 or higher
B: 80–89
C: 70–79
D: 60–69
F: Below 60

A grade of C or higher is considered passing.

## Project Files
go.mod: Defines the Go module and required Go version.
grade_calculator.go: Contains the grade calculation logic.
grade_calculator_test.go: Contains unit tests for checking the calculator's results.

## Running Unit Tests

Open a terminal in the root directory of the repository.

Navigate to the Go project folder:
cd grade-calculator

Run all unit tests:
go test ./...

The command shows which tests pass or fail.

## Checking Code Coverage

From the grade-calculator folder, run:
go test -coverprofile=coverage.out ./...

Code coverage shows how much of the program is executed during testing.