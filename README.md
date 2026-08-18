# Bioinformatics Git Practice

This repository is a small practice project created to learn Git and GitHub through a simple bioinformatics-oriented workflow.

## About the Project

The main goal of this repository is to practice version control concepts that are commonly used in bioinformatics projects.

The repository contains a simple Bash analysis script and examples of Git workflow management.

## Repository Contents

- `analysis.sh` - Example Bash script used to practice version control
- `.gitignore` - Defines files and directories that should not be tracked by Git
- `README.md` - Project documentation

## Skills Practiced

During this project, the following Git and GitHub concepts are practiced:

- Creating a Git repository
- Tracking files
- Staging changes
- Creating commits
- Viewing commit history
- Comparing file versions
- Working with remote repositories
- Pushing commits to GitHub
- Fetching and pulling remote changes
- Creating branches
- Merging branches
- Using `.gitignore`
- Writing basic project documentation

## Running the Script

Run the example Bash script with:

```bash
bash analysis.sh
```

## Example Workflow

A typical Git workflow used in this repository is:

```text
Modify files
    ↓
git status
    ↓
git diff
    ↓
git add
    ↓
git commit
    ↓
git push
```

## Bioinformatics Connection

Version control is important in bioinformatics because analysis scripts and pipelines change over time.

Git helps keep track of:

- Bash scripts
- Python and R scripts
- Workflow files
- Configuration files
- Analysis documentation

Large raw sequencing files such as FASTQ and BAM files are generally not stored directly in a normal Git repository. Instead, the repository usually contains the scripts and instructions required to reproduce the analysis.

## Author

Uğurcan Akın

Molecular Biology and Genetics student interested in bioinformatics and computational biology.
