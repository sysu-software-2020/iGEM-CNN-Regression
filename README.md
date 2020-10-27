# iGEM-CNN-Regression
This is a model that based on open-source TF-biding-score database.  
## Data Source
1. Reddy TB, Riley R, Wymore F, Montgomery P, DeCaprio D, Engels R, Gellesch M, Hubble J, Jen D, Jin H, Koehrsen M, Larson L, Mao M, Nitzberg M, Sisk P, Stolte C, Weiner B, White J, Zachariah ZK, Sherlock G, Galagan JE, Ball CA, Schoolnik GK. TB database: an integrated platform for tuberculosis research. Nucleic Acids Res. 2009 Jan;37(Database issue):D499-508. doi: 10.1093/nar/gkn652. Epub 2008 Oct 3. PMID: 18835847; PMCID: PMC2686437.  
2. Ivan Yevshin, Ruslan Sharipov, Semyon Kolmykov, Yury Kondrakhin, Fedor Kolpakov, GTRD: a database on gene transcription regulation—2019 update, Nucleic Acids Research, Volume 47, Issue D1, 08 January 2019, Pages D100–D105, https://doi.org/10.1093/nar/gky1128  

## Data preprocessing
Since DNA and TF are both made up of a limited number of known components, inspring me of using one-hot encoding.   
One-hot encoding Digitize the characteristics of the classified values, here is an example shows how DNA could be encoded into matrix form to fit deep learning.

![DNA-One-hot-encoding](imgs/one_hot_encoding.png)


## IGEM graphic model
See our (raw) model here: https://github.com/Lorisyy/iGEM-CNN-Regression/blob/main/CNN_wiki_v2.pdf




This may confuse you somewhere, please contact me.
