# Reproducibility

This folder describes how to reproduce data, code, and experiments for **PolicyPulse**.

## Data

- **Acquisition:** See the [main README](../README.md#data-sources) for the three Kaggle datasets (US Congress Bills, BillSum, Congressional Voting Records). Use Kaggle API or manual download; version and access notes will be added here.
- **Storage:** Data will be ingested into Snowflake via stages, Snowpipe, and batch load as described in the [proposal](../proposal/Data_Analytics_Project_Proposal.pdf).
- **Paths:** Raw and processed data paths will be documented as the pipeline is implemented.

## Code & Environment

- **Repository:** All code, notebooks, and scripts are maintained in this GitHub repository.
- **Environment:** Requirements (e.g., `requirements.txt`, conda env, Snowflake environment) will be added here.
- **Notebooks:** Snowpark/Python notebooks and SQL scripts will be in the repo with a clear run order.

## Experiments

- **Evaluation:** Metrics (faithfulness, citation precision, NL2SQL accuracy, ambiguity handling, latency) and evaluation scripts will be documented here.
- **Run instructions:** Step-by-step commands for ingestion, transforms, and evaluation will be added as the system is built.
- **Experiment logs:** Fixed seeds, configuration files, and run IDs will be stored here or linked.

---

*This section will be updated as the project progresses.*
