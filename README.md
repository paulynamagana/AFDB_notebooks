# AlphaFold DB notebooks

This repository contains a collection of Jupyter notebooks designed to help users access, query, and analyse protein structures from the AlphaFold Protein Structure Database (AFDB). Each notebook demonstrates a different method for interacting with the database.

## Notebooks Overview

- **AFDB_3DBeacons.ipynb**

Best for: Discovering structures across multiple databases and performing sequence-based searches.
Demonstrates how to access AlphaFold models through the 3D-Beacons Network, a federated network of protein structure data resources.

- **AFDB_API.ipynb**

Best for: Quick, direct programmatic access to specific protein entries and visualisation.
Provides a tutorial on using the direct AlphaFold Database API endpoints to retrieve data for specific proteins.

- **AFDB_BigQuery.ipynb**

Best for: Complex queries, metadata analysis, and filtering the entire dataset (200M+ structures).
Explains how to use Google BigQuery to search the massive metadata table of the AlphaFold DB.

- **AFDB_FTP.ipynb**

Best for: Bulk downloading of entire proteomes or large datasets.
Provides instructions and code to access the AlphaFold DB FTP server for bulk data retrieval.

- **AFDB_MSA_Coverage.ipynb**

Best for: Assessing the quality and evolutionary depth of the input data behind an AlphaFold prediction.
Visualises the "coverage landscape" of the Multiple Sequence Alignment (MSA)
