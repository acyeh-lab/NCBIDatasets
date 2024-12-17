# NCBI Datasets
NCBI Datasets is a modern command-line tool for accessing genome data.  Website is here: "https://www.ncbi.nlm.nih.gov/datasets/".

## Install NCBI Datasets
```
curl -o datasets 'https://ftp.ncbi.nlm.nih.gov/pub/datasets/command-line/v2/linux-amd64/datasets'
chmod +x datasets
```
# Download Genome for a particular taxa
```
./datasets download genome taxon 1232426 --filename genome.zip
```
