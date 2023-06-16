
To access the replication package, please kindly unzip the folder named "icse2023-paper908-replication-pkg.zip".

This replication package contains 5 folders. The majority of the files is data and results generated from the key processes described in the paper. The folders and description of each file are presented below.

== Folder: accepted-paper ==
File: icse2023-paper908.pdf
This is a copy of this accepted paper in PDF format. It can be easily opened using any PDF reader programme.

== Folder: code ==
File: 10-calculate-agreement-published.ipynb
Relevant section in the manuscript: Section IV-C
This is a Jupyter notebook for calculating inter-rater agreement. It can be opened using Visual Studio Code or other compatible code editors.
It uses files 6-cve-coder1, 7-cve-coder2, 8-cwe-coder1 and 9-cwe-coder2 in the data folder as data inputs.
You can place those four files in a folder in your device, then input the folder path in the source code as marked. Finally, you can run all the code in the file to generate the CWE and CVE agreement between two coders.

== Folder: common-weaknesses ==
File: 12-RQ3-common-weaknesses.pdf
Relevant section in the manuscript: Section V
This file contains a list of 11 newly proposed common privacy weaknesses with their detailed description. It can be easily opened using any PDF reader programme.

== Folder: data ==
File: 1-RQ1-privacy-related-cwe.xlsx
Relevant section in the manuscript: Section III
This file contains all the CWE entries in research concept and software development views.
The CWE entries were downloaded from the CWE website (available at https://cwe.mitre.org/data/downloads.html). 
We followed the approach explained in Section III-A to identify the privacy-related CWE entries. 
The CWE entries labelled with 1 in the "privacy-related" column are the privacy-related CWE.

File: 2-RQ1-privacy-related-cve.xlsx
Relevant section in the manuscript: Section III
This file contains all the CVE entries.
The CVE entries were also downloaded from the CVE website (available at https://cve.mitre.org/data/downloads/).
We followed the approach explained in Section III-A to identify the privacy-related CVE entries. 
The CVE entries labelled with 1 in the "privacy-related" column are the privacy-related CVE.

File: 3-RQ2-classification-to-privacy-threats.xlsx
Relevant section in the manuscript: Section IV-C
This file contains the CWE/CVE to privacy threats classification results between two coders.
There are 5 sheets in the file.
Sheet 1: Label - contains a mapping list (number-privacy threats)
Sheet 2: cwe-classification - contains the CWE to privacy threats classification results of both coders.
Sheet 3: cve-classification - contains the CVE to privacy threats classification results of both coders.
Sheet 4: cwe-classification-final - contains the final result of CWE to privacy threats classification after disagreement resolution.
Sheet 5: cve-classification-final - contains the final result of CWE to privacy threats classification after disagreement resolution.

File: 4-RQ2-explanatory-study-papers.xlsx
Relevant section in the manuscript: Section IV-A
This file contains a list of research papers with their metadata and associated privacy threats found in the explanatory study.
The metadata of the research papers was directly extracted from the selected academic databases.
The steps used to filter the relevant research papers are described in Section IV-A.

File: 5-cve-to-cwe-to-threats.xlsx
Relevant section in the manuscript: Section IV-C
This file contains the mapping from CVE records to their associated CWE records and privacy threats.

File: 6-cve-coder1.csv
Relevant section in the manuscript: Section IV-C
This file contains the result of classifying CVE to the identified privacy threats by coder 1. It is the input for inter-rater agreement calculation (see code folder).

File: 7-cve-coder2.csv
Relevant section in the manuscript: Section IV-C
This file contains the result of classifying CVE to the identified privacy threats by coder 2. It is the input for inter-rater agreement calculation (see code folder).

File: 8-cwe-coder1.csv
Relevant section in the manuscript: Section IV-C
This file contains the result of classifying CWE to the identified privacy threats by coder 1. It is the input for inter-rater agreement calculation (see code folder).

File: 9-cwe-coder2.csv
Relevant section in the manuscript: Section IV-C
This file contains the result of classifying CWE to the identified privacy threats by coder 2. It is the input for inter-rater agreement calculation (see code folder).

File: 13-summary-papers-with-venues.xlsx
Relevant section in the manuscript: Section IV-A
This file includes a full list of the selected SE publication venues with the total number of retrieved papers, 
included papers and threats found in a particular venue.

File: 14-rights.xlsx
Relevant section in the manuscript: Section IV-B
This file lists all the individual rights we extracted from the selected data protection regulations/privacy acts.
Each right is associated with the description and relevant data protection regulations/privacy acts in which the right
is mentioned.

File: 15-papers-by-threats-categories.xlsx
Relevant section in the manuscript: Section IV-A
This file summarised the number of papers that addresses each threat category.

== Folder: taxonomy ==
File: 11-Taxonomy-of-privacy-vulnerabilities.png
Relevant section in the manuscript: Section IV-B
This is a full taxonomy of common privacy threats identified in our study. It contains the threats in both vulnerabilities and compliance categories.
It is represented in a figure in PNG format.

********************** END OF README FILE **********************




