# Outfit-Category-Classification-using-Deep-Learning-and-Computer-Vision
Categorization of items into compatible outfits using a CNN model and a finetuned MobileNetV2 model using pytorch - EE599 CV project

# Dataset description

Polyvore Outﬁts is a real-world dataset created based on users’ preferences of outﬁt conﬁgurations on an online website named polyvore.com: items within the outﬁts that receive high-ratings are considered compatible and vice versa. It contains a total of 365,054 items and 68,306 outﬁts. The maximum number of items per outﬁt is 19. The images and json files are available at: https://drive.google.com/file/d/1ZCDRRh4wrYDq0O3FOptSlBpQFoe0zHTw/view?usp=sharing

# File description
         dataloader.py: Data preprocessing and loading.
         model.py: CNN model
         Category.py: model built using pretrained mobilenet
         utils.py: hyperparameters and file paths

To install the complete list of dependencies, run:

         pip install -r requirements.txt

# Running the code:
Set the parameters in utils.py. The code uses CUDA which needs an Nvidia GPU. If not using a GPU, set use_cuda flag to False in utils.py.

References
[1] https://github.com/davidsonic/EE599-CV-Project
