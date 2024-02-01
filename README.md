# violin-part-classifier
NOTE: The data we used is confidential and cannot be uploaded here (Attained from the Cozio Archive). But please feel free to look at our code! \\
Credits: Worked with Nathaniel Tunggal on this project.
We use a convolutional neural network to classify parts of a violin.
This program makes 11 different classifications listed below:
    back: violin_back
    bb: back_zoom
    bside: violin_left
    fb: front_zoom
    front: scroll_front
    head: scroll_left
    label: label
    rear: scroll_back
    top: violin_front
    treb: scroll_right
    tside: violin_right
This project is based on the cifar-10 pytorch tutorial, which we adapted for the purposes of this classification task.
We achieve 98% accuracy with this model (4 epochs and 20,000 images).

## Resources
Patrick Loeber PyTorch Tutorial 14 - CNN
https://www.youtube.com/watch?v=pDdP0TFzsoQ&list=PLqnslRFeH2UrcDBWF5mfPGpqQDSta6VK4&index=14

Building custom datasets in pytorch
https://www.youtube.com/watch?v=ZoZHd0Zm3RY

Pytorch dataloading
https://pytorch.org/tutorials/beginner/data_loading_tutorial.html
