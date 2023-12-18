# DL-Genomics-Final

## Contributors 
Bumjin Joo, Evan Li, Gabrielle Shieh, Pavani Nerella and Serdar Sungun

## Work On Google Colab
To access more computational resources, we ran all of our code through Google Colab

The original Colab files can be accessed here [DeepBio Shared Drive](https://drive.google.com/drive/u/1/folders/0ADcLAXM-v32wUk9PVA)

## File Descriptions
* `Full_Model.ipynb` was the main file through which we ran training and validation steps. 
* `HiC_Visualization.ipynb` imported trained weights, predicted, and visualized high resolution HiC matrices
* `data preprocessing/Processing_Data.ipynb` was used to generate aligned GM12878 epigenomic and HiC features. These can be seen in the shared Drive directory `DeepBio/GC Merge Data/data/E116/10000/`. Many preprocessing tools were inspired by or directly utilized their counterparts from GC Merge.
* `data preprocessing/Data_Test.ipynb` was used to validate that our preprocessed data files contained the correct data.