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
