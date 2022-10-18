# last-successful-build-action
This action searches for the last successful workflow-run for the given workflow-name and branch. The sha of the workflow-commit is set as output-parameter. If no matching workflow exists, the sha of the current run is emitted.
