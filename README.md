# Segmentation-using-UNet-Architecture
Computer_vision Project Group15
This repositories are designed to wrap up the codes based on respective dataset to make each python file work independently.

## Dataset used:
- MNIST 
- PennFudan
- Cityscape

## Repository contain following codes:
- Cityscape_extracting_pedestrian_Group_15_class.ipynb - Used for generating the pedestrain class alone from the 30 given classes which includes creating seperate target mask needed for semantic segmentation. Resizing the actual image to 400x400
- Mnist_class__Multiclass_Group15.ipynb - Code contains dataset creation of MNIST dataset to an image size of 128x128 and corresponding Unet models of varying parameters size
- Pedestrian_class_pennfudan_Group_15.ipynb - Code contains dataset creation of Penn Fudan dataset to an image size of 400x400 which involves segregating the instance segmentation data to semantic segmentation data.It also contains corresponding Unet models of varying parameters size which are evaluated using IOU metrics.
- Pedestrian_class_cityscape_Group_15.ipynb - Code contains corresponding Unet models of varying parameters size mainly to study impact of transfer learning which are evaluated using IOU metrics.

## Code helps to understand:
- basics of semantic segmentation
- Understand the architecture design of unet and power to generalise from binary to multiclass segmentation
- Impact of the number of parameters across with dataset complexity in accuracy(IOU)
- basic code to implement transfer learning from one dataset to other. In our case PennFudan dataset taken as pretrained model and tuned for cityscape. 

###### Results of trained models can be found in below link: 
https://drive.google.com/drive/folders/1qTPH9vaelcGyyxCyFr22LUKC2Un9zYnu?usp=sharing

###### For complete explanation checkout our blog: 
https://medium.com/@arvindwaskarthik/pedestrian-segmentation-a-study-of-influence-of-parameters-and-datasets-with-unet-716162bac05f
