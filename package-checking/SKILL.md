---
name: package-checking
description: Check whether packages listed in requirements.txt exist in  the Conda virtual environment and show the unexisted packages.
allowed-tools: Read Write Edit
license: MIT license
metadata:
    vision: "1.0"
    last-viewed: "2026.10.21"
    author: Jaker     
---

# Package Checking

## Overview

Package Checking is a tool to help user have a quick check whether the packages listed in requirements.txt exist in the Conda virtual environment when using the existing the virtual environment  which has intalled a number of packages.

## When to Use This Skill

This skill should be used when:

- Check the existence of the packages listed in requirements.txt in the virtual environment

- show a list of packages unexisted in the virtual environment

## Appraisal Workflow

1. **Filter the package names.** Record package names in the requirements.txt. Ignore the verison of packages.

2. **Obtain packages in virtual environment.** Activate project's conda virtual environment. Use commend "pop list" or "conda list" to obtain all installed packages of this virtual environment.

3. **Compare the two package list above.** Check whehter the packages listed in reuqirements.txt exist the virtual environment. 

4. **Output the result.** Output all uninstalled packages in the virtual environment but listed in the requirements.txt.

## 


