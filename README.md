Repository used for the implementation of the experiments in the Master Thesis named: **"Multi-center, multi-vendor automated segmentation of left ventricular anatomy in contrast-enhanced MRI"**. 

1. **ModelLearningImplementation.ipynb**: It contains the model training and validation following the implementation detailed in this work: 


    a) The data of the single-center dataset is loaded and prepared to be processed. 
    
    
    b) The data is processed with the option to include data augmentation. 
    
    
    c) Some visualisations of the data with their corresponding groundtruth are included to prove that the data is well prepared. 
    
    
    d) The hyperparameters are defined, together with the model, the optimizer, the loss function and the metric.
    
    
    e) The training and validation steps are executed, while the model with the best validation metric is saved.
    
    
    f) Finally a plot of the loss and metric evaluation during the process is included. 
    
    
2. **TLImplementation.ipynb**: Here the same steps included in the script named *ModelLearningImplementation.ipynb* are followed, but instead the pre-trained model is first loaded to be fine-tuned.  
3. **Testing.ipynb**: This code can be used to test a model across the different centers in our dataset.


    a) The multi-center dataset is loaded and prepared to be processed.
    
    
    b) The data is processed with the option to include histogram matching.
    
    
    c) Some visualisations of the data with their corresponding groundtruth are included to prove that the data is well prepared. 
    
    
    d) The model is defined and loaded. 
    
    
    e) After defining the metric the model is evaluated in each center. 
    
    
    f) Finally, some visualisation of the predictions with their corresponding groundtruths are included to visually analyse the results. 
    
    
The implementation of the CycleGAN model is not in the repository since the original code was used in this case. It can be found here: [Link to CycleGAN GitHub repository] (https://github.com/junyanz/pytorch-CycleGAN-and-pix2pix)

![figure13](https://user-images.githubusercontent.com/55059507/124180802-030c3700-dab5-11eb-9755-658753f2fd80.PNG)

