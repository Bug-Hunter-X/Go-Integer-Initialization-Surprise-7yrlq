# Go Integer Initialization Surprise

This repository demonstrates a subtle but common error in Go related to the default initialization of integer variables.

## The Bug

The `bug.go` file contains a simple Go program that initializes an integer variable `i` without explicitly assigning a value.  The program then attempts to increment `i` and print its value.  The unexpected behavior is that the initial printed value is 0, but what happens after the increment isn't as intuitive to beginners.