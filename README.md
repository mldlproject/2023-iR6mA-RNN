# iR6mA-RNN: Identifying N6-Methyladenosine Sites in Eukaryotic Transcriptomes using RNNs


#### [B. P. Nguyen](https://homepages.ecs.vuw.ac.nz/~nguyenb5/about.html)∗, T.-H. Nguyen-Vo, L. Nguyen, Q. H. Trinh, T. T. T. Do, and C. Baliuag 

![alt text](https://github.com/mldlproject/2023-iR6mA-RNN/blob/main/iR6mA_RNN_abs.svg)

## Motivation
As a common biological event observed in all living creatures, RNA modification is an essential post-transcriptional
factor that regulates the activity, localization, and stability of RNAs. Multiple diseases are associated with RNA modification.
N6-methyladenosine (6mA) modification of RNA is one of the most frequent events that affect the translational processes and
structural stability of modified transcripts and control transcriptional processes in cell state maintenance and transition.
To detect 6mA sites in eukaryotic transcriptomes, numerous computational models were introduced to assist experimental
scientists to reduce human effort and budget. These published computational frameworks are highly diverse in modeling methods and data 
sources and thus provide researchers with many options. Most online web servers of these frameworks, however, are now either unsupported or inaccessible.

## Results
Experimental results confirmed that iR6mA-RNN is an effective prediction framework to identify 6mA sites in eukaryotic transcriptomes. 
The 5-fold cross-validation suggested that the model specified with 2 LSTM layers and the triplet sliding window of 3 is the most suitable architecture for
this problem. The benchmarking experiments pointed out that our model had better performance compared to the existing accessible frameworks. 
The modeling experiments under multiple random sampling trials proved the model’s stability and robustness.

## Availability and implementation
Source code and data are available upon request. 

## Web-based Application
- Source 1: [Click here](http://14.231.233.168:5005/)
- Source 2: [Click here](http://124.197.54.240:5005/)


## Contact 
[Go to contact information](https://homepages.ecs.vuw.ac.nz/~nguyenb5/contact.html)
