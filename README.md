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
The dataset contains two folders:

MMHS11K_RGB_train.rar: This folder contains the training images in RGB format. It includes two subfolders: Hate and No-Hate. For each tweet in the MMHS11K_train.xlsx file, the corresponding image is stored in the appropriate subfolder (Hate or No-Hate) within the MMHS11K_RGB_train folder, using the tweet's Tweet_Id as the filename. For example, the image for Tweet_Id = 1596192893743796224 is stored in the No-Hate subfolder of MMHS11K_RGB_train, as this tweet is labeled as No-Hate.

MMHS11K_RGB_test.rar: This folder contains the test images in RGB format. It also includes two subfolders: Hate and No-Hate.
