# DSP Challenge — Team Repository Template

This repository stores all source code, data, documents, and evidence of the team’s work.

## Getting started

1. Rename the repository using your team/topic identifier.
2. Fill in [GROUP_INFO.md](GROUP_INFO.md).
3. Read [docs/interface.md](docs/interface.md) and complete your interface specification.
4. Update [configs/project.yaml](configs/project.yaml).
5. Put source code in src/, data in data/, reports in reports/, and slides in slides/.
6. Keep the work log up to date in logs/.

## Repository structure

```text
.
├── GROUP_INFO.md                 # Team and topic information
├── AI_USAGE.md                   # AI usage declaration
├── README.md
├── configs/                      # Run configuration and interface version
├── docs/                         # Model, interface, and usage documentation
├── src/
│   ├── data_generator/           # Baseline and advanced data generators
│   ├── algorithm/                # Baseline and advanced algorithms
│   └── evaluator/                # Metrics, evaluator, and validator
├── data/
│   ├── baseline/                 # Public baseline data
│   ├── advanced/                 # Team-generated advanced data
│   └── tests/                    # Test data and test cases
├── reports/                      # Technical report and appendices
├── slides/                       # Presentation slides
├── logs/
│   ├── meetings/                 # Meeting minutes
│   └── work/                     # Work logs
└── artifacts/                    # Run results, plots, demos, and evidence
```

## Challenge data for other teams

Challenge datasets must be uploaded to the shared [Google Drive folder](https://drive.google.com/drive/folders/1ITuDtuFODzus5bAaQVihR5sXhCHIapS5?usp=sharing).

Inside that shared folder, use the following structure:

```text
Projects/
└── Project-1/
    ├── Team-01/
    ├── Team-02/
    ├── Team-03/
    └── ...
```

Each team must:

1. Create one folder named `Team-xx` inside `Projects/Project-1/`.
2. Upload its challenge datasets into that team folder.
3. Keep the folder name consistent with the team ID in `GROUP_INFO.md`.
4. Include a short `README.md` or `manifest` describing each dataset, its configuration, its expected format, and the reason why the simulated cases are realistic.
5. Do not upload passwords, tokens, personal data, or unrelated files.

The repository should contain the generator and documentation for the challenge data; the shared Drive folder stores the data files used to challenge the other teams.

## Important rules

- Do not commit passwords, tokens, personal data, or local environment files.
- Every important simulated dataset must have a description and justification in the documentation.
- Commits do not replace work logs. Logs should record what was tried, what happened, and what decisions were made.
- Every component must include instructions for reproducing its results.
- Ask the instructor before using Git LFS or external storage for large files.

## Minimum run commands

Fill in the team’s actual commands here:

```text
# Install the environment

# Generate baseline data

# Generate advanced data

# Run the algorithm

# Run the evaluator
```
