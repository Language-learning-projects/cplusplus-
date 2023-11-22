# C++ file organizer

This repository contains code of a learning project called: "C++ file organizer".

It's purpose is to build a file organizer which can organize files based on their extensions in the user preferred way.

## Idea

The C++ file organizer will sort files by extension, using standard library I/O functions for file operations. Users can choose to run it on a single directory or recursively on subdirectories. They can also specify the start and result folders. The program uses depth-first search and hash tables for efficient file management, and provides customization options for user convenience.

## Learning

- C++
- Memory management
- I/O functions
- Hash tables
- Depth-first search

## Requirements

- A user must be able to create or remove groups.
- A user must be able to add or remove extensions from a group.
- The user must have certain groups and extensions by default (.png and .jpg in group images).
- The user must be able to specify a directory to start the organizer from.
- The user must be able to specify whether it should recursively go through folders or stay on the start directory.
- The user must be able to use a whitelist or blacklist to recursively go through folders.
- The user must be able to specify a target location for certain group files (images go to C:\Users\{user}\images)
