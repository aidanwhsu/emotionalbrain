# data structure

X_train, X_test, consist of 3D fMRI volumes y_train, y_test are the
labels used for training and testing.

X_train contains a total of 740 3D fMRI volumes, from the first 4 runs
of all subjects X_test contains a total of 185 3D fMRI volumes, from the
5th run of all subjects

# downloading dataset into drive
In order to use the dataset [1] in colab, we decided to store the relatively small dataset in google drive.
download dataset from :
https://openneuro.org/datasets/ds003548/versions/1.0.0 
upload the dataset into google drive such that the following filepath looks like:
/content/MyDrive/Me/Images/ds003548

## Running Code

The colab is separated into multiple sections. To run the colab, after
downloading the data, simply run sections: \"import\", \"data\", \"train
test split \"and \"Pytorch model\". Do note that the runtime required is
quite long.

## References 
[1] David, Olalde-Mathieu et al. Emotion Category and
Face Perception Task Optimized for Multivariate Pattern Analysis.
OpenNeuro. \[Dataset\] doi: 10.18112/openneuro.ds003548.v1.0.1
