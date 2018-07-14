# dn_data
This repository has data set to train the Deep Learning network for experimental.

## 17floweres.reorg.tgz
An archive which has directories to fit to the  [flow_from_directory of keras](https://keras.io/preprocessing/image/#flow_from_directory). The structure is like this : 

    +train_images
    |   +Daffodil
    |   |    image_0001.jpg
    |   |    image_0002.jpg
    |   |    image_0003.jpg
    |   |    ...
    |   +Daisy
    |   +Cowslip
    |    ...
    +test_images
        +Daffodil
        +Daisy
        +Cowslip
         ...

Where train_images for training. test_images for validation. Each subdirecotries ( Daffodri, Daisy,...) represent the classes of the floweres. Each training classes contains 170 images. Each validation classes has 10 images. There is not overlapping between trainign and validation.

All jpg files are from the [17floweres](http://www.robots.ox.ac.uk/~vgg/data/flowers/17/)

## 17floweres_reorg.ipynb
Google colaboratory program to download the archive from the [17floweres](http://www.robots.ox.ac.uk/~vgg/data/flowers/17/), and reorganize it to the 17floweres.reorg.tgz. This program is based on the program from the  [VGG16のFine-tuningによる17種類の花の分類 - 人工知能に関する断創録](http://aidiary.hatenablog.com/entry/20170131/1485864665)

## carvsmotorcycle.tgz
2 Classes collection of the JPEG files. 

    +train_images
    |   +car
    |   +motorcycle
    +test_images
        +car
        +motorcycles

Each classes have 80 and 20 pictures for training and testing respectively.

## test.tgz
A small collection for test by human being. It has only "test" subdirectory.


