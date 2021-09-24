# Checkpoint 1

## Execution Instructions

In order to run the pipeline, add the database as "cpdb.db" in the data directory.

If you do not see the data directory, run the following command.

`
make prep
`

After you are sure that database is in the data folder, you can run the following command to execute the whole pipeline.

`
make run
`

Alternatively, you can run the SQL scripts found the sql_scripts directory in your SQL editor.

After you finished running the pipeline, you can clean the workspace with the following commands:

To clean temporary files:
`
make clean
`

To remove the database:
`
make clean-data
`

To remove result files:
`
make clean-results
`

To clean everything except for the code:
`
make clean-full
`

After running the pipeline, you can access the logs in the logs directory.

## References

Used [this](https://github.com/iryzhkov/data-science/tree/master/workflow_template) template for the pipeline.
