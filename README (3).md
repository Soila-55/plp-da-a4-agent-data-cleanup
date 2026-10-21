# PLP Data Analysis Assignment 4 - Agent Data Cleanup

## Project Summary
Automated Python cleaning pipeline designed to process transaction telemetry and mapping registries under strict compliance guidelines.

## Execution Instructions
1. Ensure libraries are ready: `pip install -r requirements.txt`
2. Recreate dataset: `python generate_data.py`
3. Clean the logs: Run `agent_cleanup.ipynb` or run python scripts importing `cleaning_pipeline`

## Dataset Statistics
- **Before Rows**: 1,000
- **After Rows**: 877
- **Duplicate IDs Removed**: 15
- **Unparseable Dates Removed**: 87
- **Unmapped Transaction Types Removed**: 21
