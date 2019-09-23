# Garden-Nerd-Flower-Recognition
Image Processing competition hosted on HackerEarth

This is a multi-classification problem with 102 types of flowers.

## Approach
- Used Pre-Trained networks like ResNets and DenseNets.
- Trained first on 64X64 sized images, followed by 128X128, followed by 224X224 sized images. ( Progressive Resizing )
- Used Image Augmentations like Cutout, Horizontal and Vertical Flips etc.
- Used techniques like MixUp
- Ensembled top 10 performing models.

### F-1 Score - 89.48 % on the Public LeaderBoard
