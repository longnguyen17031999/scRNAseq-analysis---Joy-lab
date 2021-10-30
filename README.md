# scRNAseq-analysis---Joy-lab

The same scRNA-seq dataset is ran in both R (using Seurat package) and Python (using Scanpy package) The results are compared in term of:
* The number of cells remained after filtering
* The time it takes to run the workflow
* CPU performance

Also, the same scRNA-seq dataset is ran with read_loom() (for loom file) and read10x() (for Cellranger count output) methods The results are compared in term of:
* The number of cells remained after filtering
* Any difference between the two methods
