Training: 

Classification using an Imagenet-pretrained ResNet34 model.
The classifier base is then used as the downsampling base for a U-Net, which segments the images to isolate solar panels.

Results:

The classifier was trained on 80% of the data, with 10% being used for validation and 10% being used as a holdout test set. On this test set, with a threshold of 0.5 differentiating positive and negative examples, the model achieved a precision of 98.8%, and a recall of 97.7%.
