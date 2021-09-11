# BigDataProcessing-LHL-FinalProject
Big data processing personal learning project using Apache Spark and Databricks.

Purpose: Understand and utilise the Apache Spark engine using Databricks to: 
1) Observe the capabilities of Spark to process 'big data' with increasing feature complexity (Metrics : Runtimes & Model Performance)
2) Observe the scalability of Spark by scaling up as well as scaling out compute nodes to see how well spark scales with distributed computing (Metrics: Runtimes)



Dataset: https://archive.ics.uci.edu/ml/datasets/HIGGS

-Constructed basic pipelines trained on entire dataset

-Used polynomial expansion to increase feature complexity and capture non-linear interactions between features

-Compared performance on a scaled-up single node (244GB Memory, 32 Cores) * a scaled-out multi node cluster (1xDriver,8xWorker, worker node resources equivalent to singlenode) 

Final Presentation (Presented infront of 40 peers): https://github.com/sambady3/BigDataProcessing-IdentifyingHiggsBoson/raw/main/Final%20Presentation.pptx

