# Spring Boot Batch demo where csv file data pull to H2-database.

#First run it as spring boot program.

#Now hit the Url link :  http://localhost:9090/h2-console/

Login in H2 db with ‘password ’ & Run these queries:

select * from USER;  <br>
select * from BATCH_STEP_EXECUTION;  <br>
select * from BATCH_JOB_EXECUTION_CONTEXT;  <br>
select * from BATCH_JOB_EXECUTION_PARAMS;  <br>
select * from BATCH_JOB_INSTANCE;  <br>
select * from BATCH_STEP_EXECUTION;  <br>
select * from BATCH_STEP_EXECUTION_CONTEXT;  <br>

#Now hit link  for spring Batch job completion : http://localhost:9090/load

#To verify, hit the Url link :  http://localhost:9090/h2-console/

And then run these queries: 

select * from USER;  <br>
select * from BATCH_STEP_EXECUTION;  <br>
select * from BATCH_JOB_EXECUTION_CONTEXT;  <br>
select * from BATCH_JOB_EXECUTION_PARAMS;  <br>
select * from BATCH_JOB_INSTANCE;  <br>
select * from BATCH_STEP_EXECUTION;  <br>
select * from BATCH_STEP_EXECUTION_CONTEXT;
