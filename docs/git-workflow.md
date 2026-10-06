# Git Workflow Documentation

## Project

Task 4 - Version-Controlled DevOps Project

## Branch Strategy

This project uses three levels of branches:

### Main

The `main` branch contains the stable version of the project.

### Dev

The `dev` branch is used for development and integration of completed features.

### Feature

Feature branches are created from `dev` for individual tasks.

Examples:

- `feature/homepage`
- `feature/documentation`

## Workflow

```text
Feature Branch
      |
      | Pull Request
      v
     Dev
      |
      | Pull Request
      v
     Main# Git Workflow Documentation

## Branch Strategy

### main

The `main` branch contains the stable version of the project.

### dev

The `dev` branch is used for development and integration of completed features.

### feature branches

Feature branches are created from `dev` for individual changes.

Example:

```text
feature/homepage
feature/documentation
