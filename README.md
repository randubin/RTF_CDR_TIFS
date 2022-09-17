# RTF_CDR_TIFS
Research repository for the paper Content Disarm and Reconstruction of RTF Files  - A Zero File Trust Methodologysubmitted to IEEE Transactions on Information Forensics and Security

Dataset
========
1. Benign clean file dataset is used from GOVDOCS1: https://digitalcorpora.org/corpora/files/
To download the Microsoft RTF dataset please click here:
https://digitalcorpora.s3.amazonaws.com/corpora/files/govdocs1/by_type/rtf.zip
2. The Malicious RTF dataset was contributed by VirusTotal for research purposes. It is avilabale for academic research, please contact VirusTotal for access: https://www.virustotal.com/gui/contact-us .
The dataset folder contains all the md5 signatures describe the files were avilable at the time of the research.

Tools used to validate the research:
====================================


A. Yara
======
A. We use the yara from the following repository: known https://github.com/ditekshen/detection/blob/master/yara/indicator_office.yar

B. RTFOBJ
==========
Is part of OLETOOLS and can be found in this link:https://github.com/decalage2/oletools we used the latest version (2022-05-09 v0.60.1 )

C. VirusTotal file detection
============================
We thank VirusTotal for providing us API upload to validate our CDR disarm results.
API documentation can be founnd here: https://developers.virustotal.com/reference/overview
Link to the SHA256 dataset descriptionL:
https://github.com/randubin/RTF_CDR_TIFS/blob/main/VirusTotal_RTF_DATASET_SHA256.csv


