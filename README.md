# Multimodal Hate Speech Detection: A Novel Deep Learning Framework for Multilingual Text and Images
Furqan Khan Saddozai1, Sahar K Badri2, Daniyal Alghazzawi2, Asad Khattak3, and Muhammad Zubair Asghar1*
1. Gomal Research Institute of Computing (GRIC), Faculty of Computing, Gomal University, D.I.Khan (KP), Pakistan
2. Information Systems Department, Faculty of Computing and Information Technology, King Abdulaziz University, 21589, Jeddah, Saudi Arabia

This repository contains the MMHS11K dataset and the code associated with the paper.
 
 
 Dataset Description:

The Multimodal Multilingual Hate Speech 11K (MMHS11K) Dataset consists of 11,000 labeled Urdu tweets with English translations, each categorized as either 'Hate' or 'No-Hate'. The dataset is divided into training (MMHS11K_train.xlsx) and test (MMHS11K_test.xlsx) files. The training file contains 8,800 records with an equal distribution (i.e., 4,400) of 'Hate' and 'No-Hate' classes. The test file contains 2,200 records with 1,100 'Hate' and 1,100 'No-Hate' samples. Each file contains six columns:
Tweet_Id: A unique identifier for the corresponding tweet.
Text: The textual content of the tweet in Urdu.
Text (English): The English translation of the corresponding Urdu tweet.
Image_Text: Text extracted from images in Urdu. If no text is extracted, the value 'NIL' is used.
Image_Text (English): The English translation of the corresponding Image_Text value. If Image_Text is 'NIL', this column also shows 'NIL'.
Label: Indicates the classification of the multimodal multilingual tweet as either 'Hate' or 'No-Hate'.

The  [MMHS11K_train.xlsx] and [MMHS11K_test.xlsx] files are archived in [MMHS11K_Dataset.rar] folder. 
The [MMHS11K_RGB_train.rar folder](https://drive.google.com/file/d/1bX7QugmnIv-r8U6xVZKjqNQuOkXsF4tc/view?usp=sharing) contains the training images in RGB format.
The [MMHS11K_RGB_test.rar folder](https://drive.google.com/file/d/1TSRPlE-mVPoUqReJTZye0fyBYmZUz_Ok/view?usp=sharing) contains the test images in RGB format.

[![DOI](https://zenodo.org/badge/DOI/10.5281/zenodo.14787594.svg)](https://doi.org/10.5281/zenodo.14787594)

