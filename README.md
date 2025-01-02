# Indonesian TikTok Cyberbullying Comments Dataset
This repository contains datasets related to our paper [Building Prediction Model for Detecting Cyberbullying using TikTok Comments](https://doi.org/10.1109/ICRAIE59459.2023.10468424).

## Data Retrieval
This research retrieved TikTok user comment data with 1,508 comments from 11 March - 17 June 2023. The goal is to identify and analyze the presence of cyberbullying on TikTok. 
Cyberbullying often involves humiliation related to a person’s physical appearance. Comments that include ridicule, insults, or body-shaming are considered examples of Cyberbullying sentences.

## Data Labeling
The comments are classified into Cyberbullying (labeled as '-1') and Non-Cyberbullying (labeled as '1).
The authors label each comment by analyzing the texts and the meaning behind the texts. 
The labeling process uses several criteria to distinguish between the two categories.
For instance, identifying words or sentences that contain demeaning language, discomfort, or direct threats directed at individuals or groups.

## Example of TikTok Comment
The data is shared for research purposes in the form of a [CSV file](https://github.com/rhiosutoyo/Indonesian-TikTok-Cyberbullying-Comments-Dataset/blob/main/Dataset-Research.csv).
The example of TikTok comment and its annotation can be seen in the table below.

|Annotation Result|TikTok Comment|
|--|--|
|-1|makannya segentong buset|
|-1|KU KIRA MUKA TERNYATA AMPELA|
|1|iya bang keren tapi janji ya ini video terakhir|
|1|GIVEAWAY Pulsa 20K untuk 1 orang pemenang caranya retweet dan follow akun aku aja ya Pemenang aku umumin tangga|

##  Citation
If you use this dataset in a scientific publication, we would appreciate using the following citations:

### Plain Text
B. A. Prameswari, H. Syafa Oktaviani, T. R. Wicaksono, B. Pieter Leonard, S. Achmad and R. Sutoyo, "Building Prediction Model for Detecting Cyberbullying using TikTok Comments," 2023 IEEE 8th International Conference on Recent Advances and Innovations in Engineering (ICRAIE), Kuala Lumpur, Malaysia, 2023, pp. 1-7, doi: 10.1109/ICRAIE59459.2023.10468424.

### BibTeX
```
@INPROCEEDINGS{10468424,
  author={Prameswari, Bunga Aura and Syafa Oktaviani, Haliza and Wicaksono, Titus Rangga and Pieter Leonard, Biben and Achmad, Said and Sutoyo, Rhio},
  booktitle={2023 IEEE 8th International Conference on Recent Advances and Innovations in Engineering (ICRAIE)}, 
  title={Building Prediction Model for Detecting Cyberbullying using TikTok Comments}, 
  year={2023},
  volume={},
  number={},
  pages={1-7},
  keywords={Technological innovation;Video on demand;Buildings;Cyberbullying;Bidirectional control;Mental health;Predictive models;Cyberbullying;TikTok;BERT;Deep Learning;Sentiment Analysis},
  doi={10.1109/ICRAIE59459.2023.10468424}}
```
