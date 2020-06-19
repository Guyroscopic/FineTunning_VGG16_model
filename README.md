Description:

In this project, I fine-tunned the VGG16 model to only predict on classes of cats and dogs. Initially the VGG16 model predicted on 1000 classes but by replacing its last layer, it could be made to predict on only two. After changing its last layer, I trained the layer's weights on the images in "Image Data.zip" file.

Files and their description...

1) Image Data.zip:

It is a compressed (.zip) file which contains 70 images of cats and 70 images of dogs.

2) finetunningVGG16.ipynb:

This is a jupter noteebook file in which the VGG16 model is downloaded, fine-tunned, and re-trained on the image data mentioned above.
The fine-tunned model had an accuracy of about 99%.

3) Split images into dirs.py:

This is a python script which allows you to create "train", "test" and "valid" directories and copy files from the "Image Dataset" to these directories according to a user specified ratio. This script aranges directories and images in a format that the "finetunningVGG16.ipynb" file expects.
