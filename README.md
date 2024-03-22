## MERLIN-Human-Testers-Experiment

This repository contains the detailed experiment design, data logs and results for an exploratory testing experiment involving game testers for the evaluation of MERLIN.

### Experiment Design and Analysis
This file contains detailed design and analysis of the experiment that we could not fit into the paper.

### C01-variants
This folder contains 35 faulty variants of the case study against proposed mutation operators and 15 correct copies, divided accorss 5 testers (HT01, Ht02,..., HT05). To run them:
```
# Navigate to the directory containing the required variant
cd /path/to/variant_directory

# Run the Python script
python flappybird.py
```

### Google Forms
This folder contains pdf of google forms used to collect data including:
- Registration Form for demographic information
- Testing Form to collect information about each variant and its kill status
- Debried Form to collect information about how we can improve this experiment in future.

### Responses
This folder contains csv files corresponding to each form with anonymized raw data.

### Result
This folder contains a single compiled csv with results.
