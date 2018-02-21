Who's a good dog? Who likes ear scratches? Well, it seems those fancy deep neural networks don't have all the answers. However, maybe they can answer that ubiquitous question we all ask when meeting a four-legged stranger: what kind of good pup is that?

In this playground competition, you are provided a strictly canine subset of ImageNet in order to practice fine-grained image categorization. How well you can tell your Norfolk Terriers from your Norwich Terriers? With 120 breeds of dogs and a limited number training images per class, you might find the problem more, err, ruff than you anticipated.

Dog Breed Classification using CNN-Base Model.ipynb
- Has the base model implementation

Dog Breed Identification (Kaggle)-Using Pretrained ResNet-50 and 3 additional hidden layers.ipynb
- Has the Intermediate Implemenatation
- Requires pretrained models to be installed in the Keras modules to work.
- Floydhub.com had the pretrained modules preinstalled with the weights.

Dog Breed Identification (Kaggle)-Using Pretrained ResNet-50 and 5 additional hidden layers.ipynb
- Has the Final Code
- Requires pretrained models to be installed in the Keras modules to work.
- Floydhub.com had the pretrained modules preinstalled with the weights.

The Abstract idea to use the pretrained models was introduced by the the author 
- https://blog.keras.io/building-powerful-image-classification-models-using-very-little-data.html
- The author is trying to classify dogs vs cats in this blog

Image preprocessing libararies were used from the Keras website:
- https://keras.io/preprocessing/image/
