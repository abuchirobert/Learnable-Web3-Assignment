# Learnable-Web3-Assignment

  **Submitted by**:		 Abuchi Robert. 
  **Path:** 					Web3

## **Explain Version Control**

Version Control is a system that tracks changes made to files and codebases over time, enabling you to go back to previous versions, compare changes, collaborate on projects efficiently, and maintain a clear history of development.

**How it works**: It stores every change as a commit with a timestamp, message, and author. You can revert to any commit, see who made what changes, and track the evolution of your project.

  
**Benefits**: Prevents accidental loss of work, facilitates collaboration among multiple developers, enables experimentation and feature branching without fear of breaking the main codebase, maintains a clear and organized history of project development.

  
  

## Difference Between Git and GitHub

 Git is a distributed version control system (DVCS) that runs locally on your computer. It manages the version history of files and codebases. GitHub is a web-based platform built on top of Git that hosts Git repositories online, providing features for collaboration, code review, issue tracking, and social coding.

Key difference: *Git is the version control system itself, while GitHub is a hosting service for Git repositories*

## 3 GitHub Alternatives:

 - GitLab, 
 - Bitbucket, 
 - SourceForge

## Difference Between Git Fetch and Git Pull

**Git Fetch** downloads new commits from a remote repository to your local repository but doesn't merge them into your current working branch. 

**Git Pull** fetches new commits and immediately merges them into your current working branch

Key difference: *Fetch retrieves changes, but Pull retrieves and integrates those changes into your working branch*

## Meaning of Git Rebase

**Git Rebase**: Reapplies commits from one branch onto another, creating a linear history without merge commits

**Command**: git rebase <base-branch>

**Example**: Rebase your feature branch onto the main branch: git rebase main

## Meaning of Git Cherry-Pick

**Git Cherry-Pick**: Selectively applies a specific commit from one branch to another

**Command**: git cherry-pick <commit-hash>

**Example**: Pick a commit from a feature branch and add it to the main branch: git cherry-pick 1234abcd