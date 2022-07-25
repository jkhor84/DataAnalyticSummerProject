# DataAnalyticSummerProject
Summary
This project is a data analytic project. This project consists of setting up a Linux host, FTP server, Hadoop file system, Spark, versioning control using Git and data analysis using R/Rstudio.

Firstly, Linux (Ubuntu 22.04 LTS) was set up on a laptop. Once Linux was set up, an FTP server (VSFTPD) was installed to enable file transfers. Then, the Hadoop file system (version: Hadoop-3.3.3) was set up to store the large datasets. Moreover, Spark (version: Spark-3.3.0) was set up as it could process data much faster than the Hadoop file system.

Git was installed in Linux to document instructions and configurations for the project.

For data analysis, R/Rstudio (version of R: 4.2; version of Rstudio: 2022.07.0+548) were installed to perform simple data analysis such as summarizing data and plotting graphs. Microbes datasets were downloaded from www.kaggle.com and stored in the Hadoop file system. Then, these datasets were fetched to R via Spark for data analysis. Using R, the microbes dataset could be summarized into groups. For example, the microbes data would be grouped into the same microorganisms with respect to their perimeter in descending order. Once those data were summarized, the desired graph could be plotted using R.
