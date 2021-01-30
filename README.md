# 16S-rRNA-analysis-pipeline

## Requirements
  
**System requirement** Windows 10 / Mac OS 10.12+ / Ubuntu 18.04  
**gitforwidnows** 2.23.0 http://gitforwindows.org/(Windows only)  
**R** 3.6.2 https://www.r-project.org/  
**Rstudio** 1.2.5019 https://www.rstudio.com/products/rstudio/download/#download  
**vsearch** v2.14.1 https://github.com/torognes/vsearch/releases  
**usearch** v10.0.240 https://www.drive5.com/usearch/download.html  

## How to use  
**1.metadata.txt is needed,including sample name,group at least,and put it into result folder.**  
![微信图片_20210130170314.png](https://i.loli.net/2021/01/30/gJuvU2jmat8yPbZ.png)

**2.Put raw data in the seq folder  seq/*.fq.gz**

**3.Specify the working directory and database location**  
#Specify database location  
db=/c/(your folder)  
  
#Specify the working directory  
wd=/c/(your folder)
  
#set export path  
export PATH=$PATH:${db}/win  
  
#enter the working directory  
cd ${wd}

## Reference   
[1]Jingying Zhang, Yong-Xin Liu, et. al. NRT1.1B is associated with root microbiota composition and nitrogen use in field-grown rice. Nature Biotechnology 37, 676-684, doi:10.1038/s41587-019-0104-4 (2019).


