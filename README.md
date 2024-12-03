**Meltano Benchmarking**

This repository supports the [self-hosted benchmark article](https://dlthub.com/blog/self-hosted-tools-benchmarking), where Meltano was benchmarked. 

### Steps Involved:

1. **Dataset Creation**:
   - Generated a TPCH dataset of approximately 6.42 GB.
   - Stored the dataset in a PostgreSQL database.

2. **Hosting**:
   - Deployed the database on a GCP-SQL PostgreSQL instance.

3. **Infrastructure Setup**:
   - Used a GCP VM with the following specifications:
     - **CPUs**: 8 cores  
     - **Memory**: 16 GB RAM  
     - **CPU Base Frequency**: 2.3 GHz  

4. **Pipeline Configuration**:
   - Built a Meltano pipeline as outlined in this repository.
  
     
Logs : [here](logs/elt/devtap-postgres-to-target-bigquery/98c0eb60-c79a-4670-a651-641bbc11c49c/elt.log)
