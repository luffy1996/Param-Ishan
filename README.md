#SuperComputer Script

You can refer to this [link](https://rohanrajblogs.blogspot.in/2017/01/supercomputer-param-ishan.html) for more details .

## Basic Tutorial

1)Submit a Job <br />
$sbatch (jobname)

2)To see all the currently running jobs.<br />
$squeue

3)See details of a job<br />
$scontrol show job (job_id)

4)To cancel a job<br />
$scancel (job_id)

5)To hold a job<br />
$scontrol hold <jon_id>

6)To release a job<br />
$scontrol release (job_id)

7)To get the details of all partition and the resources being used <br />
$sinfo

##Environment Modules

1)Modules available<br /> 
$module avail

2)Modules loaded to your account<br />
$module list

3)To load a module <br />
$module load (name)

4)To unload a module <br />
$module unload (name)

###NOTE
1)In case you want to use GPU, you have to do a GPU login. Login takes place in a simple loop of CPU -> GPU -> MIC. Suppose you get a MIC login , you need to exit it. The next time you login , you will have a CPU login . In this manner the login works. <br />
2)In case you get stuck up after MIC login, stop(CTRL + C) it and try once more.<br />
 
