#SuperComputer Script

You can refer to this [link]() for more details .

## Basic Tutorial

1)Submit a Job
$sbatch <jobname>

2)To see all the currently running jobs.
$squeue

3)See details of a job
$scontrol show job <job_id>

4)To cancel a job
$scancel <job_id>

5)To hold a job
$scontrol hold <jon_id>

6)To release a job
$scontrol release <job_id>

7)To get the details of all partition and the resources being used
$sinfo

##Environment Modules

1)All the modules available 
$module avail

2)Modules already loaded to your account
$module list

3)To load a module 
$module load <name>

4)To unload a module 
$module unload <name>
 
