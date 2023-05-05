# CIFAR10_MNIST_CNN_and_Transfer_Learning
Image classification using CNN model build from scratch and transfer learning
The code was run in Google Collab, and I used the google drive as the storage device. For this reason, I had two code cells above every code here. If you wish to run it in a separate system, or even in Google Collab, please consider changing the directory folder to the folder you placed the code.

These two cells of codes are as follows:

### Cell 1:
```
from google.colab import drive
drive.mount('/content/drive')
```
### Cell 2:
```
cd "/content/drive/MyDrive/Spring_2023_Project/COMS_572_Source_Code/MNIST"
```
or,
```
cd "/content/drive/MyDrive/Spring_2023_Project/COMS_572_Source_Code/CIFAR10"
```
We have created four image classification models in this project. We will guide you now how to build each one of them.

1. CNN Model for MNIST dataset:


    a.	Locate file ”\MNIST\MNIST_self_build.ipynb”
    
    b.	Change the first two cells as mentioned in the top of the document
    
    c.	Run all the code blocks

    d.	You will get the model as 'MNIST_self_build_model.h5' in the directory.
2.	Transfer Learning (VGG-19) Model for MNIST dataset:

    a.	Due to ram restrictions, we have developed the model in four stages.
    
    b.	We need to run four scripts sequentially.

    c.	First locate the file “\MNIST\MNIST_VGG19_first_stage.ipynb”

    d.	Run all the code blocks

    e.	You will get the model as 'epoch10_stage_1_MNIST_VGG_build_model.h5' and 'epoch10_stage_1_lr.txt' in the directory.

    f.	Then locate the file “\MNIST\MNIST_VGG19_second_stage.ipynb”

    g.	Run all the code blocks

    h.	You will get the model as 'epoch10_stage_2_MNIST_VGG_build_model.h5' and 'epoch10_stage_2_lr.txt' in the directory.

    i.	Then locate the file “\MNIST\MNIST_VGG19_third_stage.ipynb”

    j.	Run all the code blocks

    k.	You will get the model as 'epoch10_stage_3_MNIST_VGG_build_model.h5' in the directory.

    l.	Then locate the file “\MNIST\MNIST_VGG19_fourth_stage.ipynb”

    m.	Run all the code blocks

    n.	You will get the model as 'epoch10_10_final_model_MNIST_VGG_build_model.h5' in the directory. This is the final VGG model for MNIST dataset.

3.	CNN Model for CIFAR10 dataset:

    a.	Locate file ”\CIFAR10\CIFAR10_self_build.ipynb”

    b.	Change the first two cells as mentioned in the top of the document

    c.	Run all the code blocks

    d.	You will get the model as 'CIFAR10_self_build_model.h5' in the directory.

4.	Transfer Learning (VGG-19) Model for CIFAR10 dataset:

    a.	Due to ram restrictions, we have developed the model in four stages.

    b.	We need to run four scripts sequentially.

    c.	First locate the file ”\CIFAR10\CIFAR10_VGG19_first_stage.ipynb”

    d.	Run all the code blocks

    e.	You will get the model as 'epoch10_stage_1_CIFAR10_VGG_build_model.h5' and 'epoch10_stage_1_lr.txt' in the directory.

    f.	Then locate the file ”\CIFAR10\CIFAR10_VGG19_second_stage.ipynb”

    g.	Run all the code blocks

    h.	You will get the model as 'epoch15_stage_2_CIFAR10_VGG_build_model.h5' and 'epoch15_stage_2_lr.txt' in the directory.

    i.	Then locate the file ”\CIFAR10\CIFAR10_VGG19_third_stage.ipynb”

    j.	Run all the code blocks

    k.	You will get the model as 'epoch10_stage_3_CIFAR10_VGG_build_model.h5' in the directory.

    l.	Then locate the file ”\CIFAR10\CIFAR10_VGG19_fourth_stage.ipynb”

    m.	Run all the code blocks

    n.	You will get the model as 'epoch10_15_final_model_CIFAR10_VGG_build_model.h5' in the directory. This is the final VGG model for MNIST dataset.


You can find the completely developed models in the following link:
https://iastate.box.com/s/sn6k5veslefltj4xltvtpqodu9oz7x59

Please let us know if you see any errors.
