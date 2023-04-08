
# CS6910 Assignment-2

The assignment contains two parts.
In Part-A, I have build CNN model from scratch using pytorch to train on iNaturalist dataset.
In Part-B, I have iported pretrained VGG16 CNN model using pytorch and modified it to make suitable for iNaturalist dataset(having only 10k train images).


## Authors

- [@Haider Altaf am22s020](https://www.github.com/HaiderAltaf)


## Part-A

### References:

### References:

- Source1- https://blog.paperspace.com/writing-cnns-from-scratch-in-pytorch/

- source2- https://pyimagesearch.com/2021/07/19/pytorch-training-your-first-convolutional-neural-network-cnn/


- source3- https://pytorch.org/docs/stable/generated/torch.nn.Dropout.html

### Libraries Used: 

- Used the pytoch, pytorchvision and other necessary libraries for the CNN model buiding and training.

### Device

- Device will determine whether to run the training on GPU or CPU.

  code: device = torch.device('cuda' if torch.cuda.is_available() else 'cpu')

### Data Pre-processing

- Created a function named data_pre_processing to upload the downloaded datasets(train and test).
- 

## Appendix

Any additional information goes here

