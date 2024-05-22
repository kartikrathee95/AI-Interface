# Batch Runs Package
## Overview
This package facilitates batch runs for your simulations.

## Installation
To install the package, follow these steps:

1. Open a terminal.
2. Change directory to `batch_runs_package`:
   ```cmd
   cd batch_runs_package
   ```
3. Run the `build_and_install.bat` script:
   ```cmd
   build_and_install.bat
   ```
## Usage
   ```cmd
   run_batches
   run_batches [--xlsx XLSX_FILE_PATH] [--csv CSV_FILE_PATH] [--SERVER_URL SERVER_URL]
   ```
Arguments
run_batches (it will run with default xlsx,csv files and default api_gateway SERVER_URL)

--xlsx XLSX_FILE_PATH: Path to the XLSX file containing batch job parameters.
--csv CSV_FILE_PATH: Path to the CSV file containing batch job parameters.
--SERVER_URL SERVER_URL: Optional. The URL of the server to send batch job results to.
