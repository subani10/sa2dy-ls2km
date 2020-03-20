# Data Retrieval

This project uses the FCX-3 dataset from the crcns.org database. This dataset contains EEG recordings taken intracranially of the frontal and parietal lobes of 7 patients hospitalized for epilepsy, during a working memory task. Below are instructions for downloadin a .gz folder for each of the 7 subjects.

Access data from the link https://portal.nersc.gov/project/crcns/download/fcx-3. This is a link to the FCX-3 dataset in the repository and will bring you to a list of folders. Under the "data" folder, download the files s1.tar.gz - s7.tar.gz. Note that a CRCNS login is required to access these files, but a free account can be created by following this link: https://crcns.org/register.

Script for unpacking the files:
```
def data_unpack(data):
    """
    unpacks the given .gz file. The argument is the file name (ex: s1.tar.gz)
    """  
    tar -zxvf data
```
    
