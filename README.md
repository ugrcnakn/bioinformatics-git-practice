# Bioinformatics Git Practice

A small bioinformatics-oriented project created to practice Git, GitHub, repository organization, and reproducible project structure.

## Project Goal

The goal of this repository is to learn how Git and GitHub can be used to manage a simple bioinformatics project.

The project demonstrates how analysis scripts, small example datasets, documentation, and Git history can be organized while keeping large raw data and generated results outside version control.

## Repository Structure

```text
bioinformatics-git-practice/
├── README.md
├── .gitignore
├── notes.txt
├── scripts/
│   └── analysis.sh
├── data/
│   ├── example/
│   │   └── example.fasta
│   └── raw/
├── logs/
└── results/
```

## Directory Description

- `scripts/` - Analysis scripts used in the project
- `data/example/` - Small example data that can be tracked with Git
- `data/raw/` - Raw sequencing data that should not be tracked
- `results/` - Generated analysis results
- `logs/` - Log files produced during analyses
- `notes.txt` - Simple project notes

## Example Data

The repository contains a small example FASTA file:

```text
data/example/example.fasta
```

Small example files are useful for testing scripts and demonstrating workflows without storing large sequencing datasets in Git.

## Running the Analysis Script

Run the example Bash script with:

```bash
bash scripts/analysis.sh
```

## Git Workflow Practiced

This project is used to practice the following workflow:

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

The project also includes practice with:

- Git repositories
- Commit history
- Branches
- Merging
- Remote repositories
- Push and pull
- `.gitignore`
- README documentation
- Project directory organization

## Data Management

Large raw sequencing files should generally not be stored directly in this repository.

The `.gitignore` file is configured so that raw data, generated results, and log files can remain on the local computer without being tracked by Git.

For this project:

```text
data/raw/  -> ignored
results/   -> ignored
*.log      -> ignored
```

Small example datasets under:

```text
data/example/
```

can still be tracked and shared through GitHub.

## Bioinformatics Connection

Bioinformatics analyses often involve large datasets and multiple analysis steps.

Git is mainly useful for tracking the parts of the project that define how the analysis is performed, such as:

- Bash scripts
- Python scripts
- R scripts
- Workflow files
- Configuration files
- Documentation
- Small reproducible example datasets

This makes it easier to understand how an analysis changed over time and helps make computational work more reproducible.

## Author

Uğurcan Akın

Molecular Biology and Genetics student interested in bioinformatics and computational biology.
