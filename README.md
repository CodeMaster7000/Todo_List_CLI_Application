# Todo_List_CLI_Application

## About

A Python program to view, create and tick off todos.

## Implementation

- For Windows users: Create a `todolist.bat` file saying `@echo off python3 todolist.py %1 %2`. Then, run `mklink todo todo.bat`.

- For Linux users: Create a `todolist.sh` file saying `python todo.py "$@"`. Then, run `$ ln -s todo.sh todo`.
