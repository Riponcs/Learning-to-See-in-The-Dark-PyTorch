# Learning to See in the Dark - Pytorch
___
This is Pytorch implementation of a famous CVPR 2018 conferrance paper "*Learning to See in the Dark*" by *Chen Chen, Qifeng Chen, Jia Xu, Vladlen Koltun*.

Link of The  [paper](https://www.crcv.ucf.edu/wp-content/uploads/2019/04/CAP6412_Spring2019_Learning_to_see_in_the_dark_Fnu_Tulha_final.pdf)

## Result
|Epoch  |PSNR Value|
|-------|----------|
|500    |27.24     |
|1000   |27.73     |
|1500   |27.93     |
|1600   |28.02     |
|1700   |28.07     |
|1800   |27.81     |
|1900   |27.95     |
|2000   |27.87     |

I ran the model for 2000 epoch and the model converge preety fast. Just after 1700 epoch **I got 28.07 PSNR value**. 


## My System Configuration:
* GPU: 2080 Ti _[This code will ran will run on any GPU if VRAM is more than 8.5GB ]_
* RAM: 32GB _[My ram usage was always 30GB+. If you want to run Train & test file at the same time 32 GB isn't enough. 48 GB recommanded]_
* Cpu: Core i9
* Time Taken: It took about 20S to run each epoch.

## Loading Dataset
* To Load the dataset, Go to this [official imlementat website](https://github.com/cchen156/Learning-to-See-in-the-Dark) and download "Sony 25 GB" dataset. or [Click Here](https://storage.googleapis.com/isl-datasets/SID/Sony.zip) to download this dataset.

