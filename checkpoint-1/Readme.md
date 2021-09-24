# Checkpoint 1 for Blue Spiders

Group Participants:
 - Harkirat Gill
 - Igor Ryzhkov
 - Susan Mulhearn

Checkpoint 1 Questions

Question 1: What is the mean and variance of the civilian complaints per year for different units?

Question 2: What is the mean and variance of the civilian complaints per year for different beats?

Question 3: What is the distribution of types of complaints for different units?

Question 4: What is the distribution of types of complaints for different beats?



Execution Instructions

In order to run the pipeline, add the database as "cpdb.db" in the data directory.

If you do not see the data directory, run the following command.

make prep

After you are sure that database is in the data folder, you can run the following command to execute the whole pipeline.

make run

Alternatively, you can run the SQL scripts found the sql_scripts directory in your SQL editor.

After you finished running the pipeline, you can clean the workspace with the following commands:

To clean temporary files: make clean

To remove the database: make clean-data

To remove result files: make clean-results

To clean everything except for the code: make clean-full

After running the pipeline, you can access the logs in the logs directory.