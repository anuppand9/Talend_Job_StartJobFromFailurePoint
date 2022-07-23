Job Name: FailureJob_Test_0.1.zip

1. Import Job in Studio.
2. Set your file path in context.
3. Set your file name in context.
4. Replace you schema for input and output.
5. Take care of Id, createddate and updateddate columns in output.
7. Define Target (Database/Flat File)
8. Start the job.
9. Whenever error occurred in job, a file will produced in file path with Last Processed Records.
10. To restart the job from same point, put the last processed records value in 'nbrow' context.
11. Start the Job again.
12. Once all data is loaded, a file will store at file for job status after checking of source/target records count.

### Input File should have Id and if not then create in Target Table.

