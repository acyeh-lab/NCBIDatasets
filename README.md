# NCBI Datasets
NCBI Datasets is a modern command-line tool for accessing genome data.  Website is here: "https://www.ncbi.nlm.nih.gov/datasets/".

## Install NCBI Datasets
```
curl -o datasets 'https://ftp.ncbi.nlm.nih.gov/pub/datasets/command-line/v2/linux-amd64/datasets'
chmod +x datasets
```
# Find Genome for a particular taxa
```
./datasets summary genome taxon "Bacteroides thetaiotaomicron" >> Bacteroides_thetaiotaomicron.txt
```
Note there are many accessions.  When we look up the "Bacteroides thetaiotaomicron" genome here: "https://www.ncbi.nlm.nih.gov/datasets/genome/?taxon=818"
We see RefSeq ```GCF_014131755.1``` is the best one.

# Download Genome for a particular taxa
```
./datasets download genome accession "Bacteroides thetaiotaomicron" --filename genome.zip
```
