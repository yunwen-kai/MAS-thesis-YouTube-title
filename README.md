# MAS-thesis-YouTube-title

## Project Background
This study focuses on fashion- and beauty- related YouTube videos to explore the relationship between title and video view counts. Beyond one’s experience on how to name a video attractively, this thesis demonstrates whether there are common patterns of word choice and sentiment between well performed videos (high view counts) and poorly per- formed videos (low view counts), and also, whether the topics are similar within fashion influencers. Besides the word itself, whether capital words have correlation with video view counts. Also, this study predict the videos’ view rank (high view counts or low view counts) with the deep learning model, BERT, by videos’ title and other quantifiable characters, including title length, video length, published dates, sentiment intensity and unsupervised learned topics by Latent Dirichlet Allocation.


## Data and Code Using Order
Data
1. full_youtuber_group1_v5.csv and full_youtuber_group1_v5.csv: Extracted from YouTube API

R code

2. thesis_youtube_group_1/2: Text mining steps for two csv data

Python

3. thesis_feature_eng_final: Feature engineering
4. bert-classification: Modeling



## Citation
```
@article{scikit-learn,
 title={Scikit-learn: Machine Learning in {P}ython},
 author={Pedregosa, F. and Varoquaux, G. and Gramfort, A. and Michel, V.
         and Thirion, B. and Grisel, O. and Blondel, M. and Prettenhofer, P.
         and Weiss, R. and Dubourg, V. and Vanderplas, J. and Passos, A. and
         Cournapeau, D. and Brucher, M. and Perrot, M. and Duchesnay, E.},
 journal={Journal of Machine Learning Research},
 volume={12},
 pages={2825--2830},
 year={2011}
}


@inproceedings{conf/icwsm/HuttoG14,
  added-at = {2015-05-25T00:00:00.000+0200},
  author = {Hutto, Clayton J. and Gilbert, Eric},
  biburl = {https://www.bibsonomy.org/bibtex/253a5741ab827539d4bc4bf836fa6dae7/dblp},
  booktitle = {ICWSM},
  crossref = {conf/icwsm/2014},
  editor = {Adar, Eytan and Resnick, Paul and Choudhury, Munmun De and Hogan, Bernie and Oh, Alice H.},
  ee = {http://www.aaai.org/ocs/index.php/ICWSM/ICWSM14/paper/view/8109},
  interhash = {e73f21d7ff21014b85f5c7b48f335a11},
  intrahash = {53a5741ab827539d4bc4bf836fa6dae7},
  isbn = {978-1-57735-659-2},
  keywords = {dblp},
  publisher = {The AAAI Press},
  timestamp = {2016-05-10T11:39:40.000+0200},
  title = {VADER: A Parsimonious Rule-Based Model for Sentiment Analysis of Social Media Text.},
  url = {http://dblp.uni-trier.de/db/conf/icwsm/icwsm2014.html#HuttoG14},
  year = 2014
}

@inproceedings{wolf-etal-2020-transformers,
    title = "Transformers: State-of-the-Art Natural Language Processing",
    author = "Thomas Wolf and Lysandre Debut and Victor Sanh and Julien Chaumond and Clement Delangue and Anthony Moi and Pierric Cistac and Tim Rault and Rémi Louf and Morgan Funtowicz and Joe Davison and Sam Shleifer and Patrick von Platen and Clara Ma and Yacine Jernite and Julien Plu and Canwen Xu and Teven Le Scao and Sylvain Gugger and Mariama Drame and Quentin Lhoest and Alexander M. Rush",
    booktitle = "Proceedings of the 2020 Conference on Empirical Methods in Natural Language Processing: System Demonstrations",
    month = oct,
    year = "2020",
    address = "Online",
    publisher = "Association for Computational Linguistics",
    url = "https://www.aclweb.org/anthology/2020.emnlp-demos.6",
    pages = "38--45"
}

@inproceedings{gu-budhkar-2021-package,
    title = "A Package for Learning on Tabular and Text Data with Transformers",
    author = "Gu, Ken  and
      Budhkar, Akshay",
    booktitle = "Proceedings of the Third Workshop on Multimodal Artificial Intelligence",
    month = jun,
    year = "2021",
    address = "Mexico City, Mexico",
    publisher = "Association for Computational Linguistics",
    url = "https://www.aclweb.org/anthology/2021.maiworkshop-1.10",
    doi = "10.18653/v1/2021.maiworkshop-1.10",
    pages = "69--73",
}
```
