
# Instruction for running method 1 and 2 (Weka projects)



## Before runing my codes

Please generate the six global features such as JCD, Tamura, ColorLayout, EdgeHistogram, Autocolorcorrelogram and PHOG using LIRE (an open source library for content-based image retrieval).
 
Create an .arff file  for the corresponding feature file.


## To run my codes


Load the data into Weka (a machine learning support library).

Use SimpleLogistic (Method 1) and logistic model tree (Method 2) classifier to train the model. 

Use 70% of the data for the training and rest of the data for the validation. 

After training a model, please use the supplied test set for the prediction of the model. 



 #Instructions for runing method 3, 4 and 5 (Python3.6 files)




How to run pretranined models to classify test set images:



## Before runing my codes


Please copy the test data folder into the folder called data/test.

Sample test folder is provided, you can replace the content of that folder.

Folder structure is important. Don't delete the sub folder in the test folder. It is required.


## To run my codes


1. Go to the src/  folder and run the corresponding "method_x.py" file using python3 command.

Ex: to run method_3:
	python3 method_3.py

(if error occured, please provide sudo permission)


 2. Then, it will ask you to enter the data folder. Then, it is required to give the absolute path of the data folder.

Ex: "/home/vajira/simula/code_samples/mediaEval_2018_final_for_submission/data"



3. At the end, it will save output files to the folder /../data/pytorch_submission_medico


## Important Notes


1. Don't delete the validaton folder and other folders


## Required packages

pytorch 4.1
numpy
pandas
itertools
matplotlib



That's all .... !

Enjoy our results....

If you have any problems: please contact me: vajira@simula.no or Debesh debesh@simula.no



Usefull commands
_______________________

for file in `find . -name *.jpg_backup` ; do mv "$file" "${file%_backup}"; done
