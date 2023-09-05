# image_maskrcnn
In this research, we used multiple dataset images to detect cancerogenous cells in whole tissues.

The data was collected in partnership with a clinic in Brazil. And it's available at the following link: https://universe.roboflow.com/carolina-rutili-de-lima/all_dataset-3jzhy


Image "epochs_and_alpha.png":

The values of a) $\alpha= 0.001$ b) $\alpha=0.0001$ c) $\alpha=0.00001$, 1 epoch took 3181s to train. As  250 epochs are not enough because we reduced $\alpha$, so we would need to train the network at least 400 epochs, which means 14 days of training.
