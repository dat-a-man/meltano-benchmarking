Melatano bench marking:
This repo is created how for [self hosted benchmark article](https://dlthub.com/blog/self-hosted-tools-benchmarking). Meltano was benchmarked.
Steps involved:

1. Created a TPCH dataset that is around 6.42 GB on postgres.
2. Hosted that on GCP-SQL postgres instance.
3. Used the VM on GCP with configurations
   CPUs: 8 cores
   Memory: 16 GB RAM
   CPU Base Frequency: 2.3 GHz
4. Created a meltano pipeline as in the repository. 
