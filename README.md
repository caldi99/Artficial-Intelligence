# ArtficialIntelligence_Project

To be able to execute the code you need to follow the following steps :
* Download the dataset from this link : https://drive.google.com/file/d/1HzrqJLkGG8TUaP1N_QkB7uaf-dtcB35H/view?usp=sharing
* Extract the content into a directory called "dataset". At the end you should have a directory that contains two folders one called "with_mask" and another one called "without_mask"
* [Optional] If you want to save some memory space and do not have any warnings when executing the code, you can replace the images that are not in the .jpg format with the actual conversion in .jpg. To make the conversion you can use the following website : https://converter.11zon.com/it/jpg-to-jpeg/
* Create a folder called "mask_detector" under the folder "models" where you will need to place the model produced at the end of the training procedure
* Create a folder called "data"
* Execute in the following sequence the jupyter notebooks : "rename_dataset.ipynb" , "data_preparation.ipynb", "training_model.ipynb"
* At the end you should have in your directory a file called "model_last.h5"
* Take the file called "model_last.h5", rename it in "model.h5" and copy into the folder "models/mask_detector"
* Finally execute the last jupyter notebook called "face_mask_detector"


Notice that to be able to execute the code you need to have some hardware and software requirements :
* Software :
    *  Anaconda, Tensorflow (Gpu Version), Opencv, Cuda
* Hardware :
    * A Nvdia Graphic Card that is as powerful or more than a GTX 970

# Team
 | <a href="https://github.com/caldi99" target="_blank">**Francesco Caldivezzi**</a> | <a href="https://github.com/simonedantimo" target="_blank">**Simone D'antimo**</a> | <a href="https://github.com/mrsingh-10" target="_blank">**Harjot Singh**</a> |
| :---: |:---:|:---:|
| [![Francesco Caldivezzi](https://avatars.githubusercontent.com/u/31403460?v=4)]()    | [![Simone D0antimo](https://avatars.githubusercontent.com/u/24751381?v=4)]() |    | [![Harjot Singh](https://avatars.githubusercontent.com/u/101326953?v=4]() |



