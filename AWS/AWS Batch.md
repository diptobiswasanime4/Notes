Created: March-17-2024

AWS Batch helps developers run batch computing workloads on [[AWS|AWS Cloud]]. [[Batch processing|Batch computing]] is a common way for developers, scientists and engineers to access large amounts of compute resources.
## Components of AWS Batch

1. **Jobs** - It is a unit of work (such as a [[Shell]] or [[PowerShell]] script, [[Linux|Linux executable]], [[Docker]] container image, etc.)
2. **Job definitions** - It specifies how jobs are to be run.
3. **Job Queues** - A job is submitted to a particular job queue where the job resides till it's scheduled to run onto a compute environment.
4. **Compute Environment** - A compute environment is a set of managed or unmanaged Compute resources, used to run jobs. Example - [[Amazon Fargate|Fargate]], [[EC2 (Elastic Compute Cloud)|EC2]], etc.
# Related Notes

1. [[AWS Docs]]
# References

1. 