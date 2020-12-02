Need anaconda installed.

To begin:
```
conda create -c bioconda -n ClustEnv clust
```

Cheatsheet: https://docs.conda.io/projects/conda/en/4.6.0/_downloads/52a95608c49671267e40c689e0bc00ca/conda-cheatsheet.pdf


On my computer:
1. activate conda environment for clust: ClustEnv
2. updata Clust:
```
source activate ClustEnv

conda update -c bioconda clust
```
3. run clust with normalized data:

```
clust norm.res.exp.data.txt -o Clust_Output_RESGenes/
```
