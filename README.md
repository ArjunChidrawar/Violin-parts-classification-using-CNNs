# violin-part-classifier
NOTE: The data we used is confidential and cannot be uploaded here (Attained from the Cozio Archive). But please feel free to look at our code! <br />
Credits: Worked with Nathaniel Tunggal on this project. <br />
We use a convolutional neural network to classify parts of a violin. <br />
This project is based on the cifar-10 pytorch tutorial, which we adapted for the purposes of this classification task.
We achieve 98% accuracy with this model (4 epochs and 20,000 images). <br />
This program makes 11 different classifications listed below: <br />
    back: violin_back <br />
    bb: back_zoom <br />
    bside: violin_left <br />
    fb: front_zoom <br />
    front: scroll_front <br />
    head: scroll_left <br />
    label: label <br />
    rear: scroll_back <br />
    top: violin_front <br />
    treb: scroll_right <br />
    tside: violin_right <br />

## Resources
Patrick Loeber PyTorch Tutorial 14 - CNN
https://www.youtube.com/watch?v=pDdP0TFzsoQ&list=PLqnslRFeH2UrcDBWF5mfPGpqQDSta6VK4&index=14

Building custom datasets in pytorch
https://www.youtube.com/watch?v=ZoZHd0Zm3RY

Pytorch dataloading
https://pytorch.org/tutorials/beginner/data_loading_tutorial.html
