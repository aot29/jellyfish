# Jellyfish
Experimenting with image preprocessing for machine learning classification of images.
Based on the Jellyfish dataset from Kaggle (Tanwar, Bandini, Burnsworth, 2024)

Jellyfish images have very diverse textures, transparencies, shapes and so pose an interesting testbed for preprocessing images to enhance classification.

## Download dataset
Download the data from https://www.kaggle.com/datasets/anshtanwar/jellyfish-types

Extract the zip file to a directory called "data". The directory structure should now look like this:
```
jellyfish
    |
    ----- data
           |
           ----- barrel_jellyfish  
                 blue_jellyfish  
                 compass_jellyfish  
                 lions_mane_jellyfish  
                 mauve_stinger_jellyfish  
                 Moon_jellyfish  
                 Train_Test_Valid
```
Each species directory has 150 jpeg images. Please note that images have different pixel sizes and that file names are not consistent.

You can ignore the "Train_Test_Valid" directory.

## Setup
Clone the repo, `cd` into it.
Create a Python virtual environment and install the required packages.
```
conda create -n jelly python=3.12.2
pip install -r requirements.txt
```

Activate the environment and start the Jupyter notebook server
```
conda activate jelly
jupyter lab
```

## References
Ansh Tanwar, Arturo Bandini, Ryan Burnsworth (2024) Jellyfish Image Dataset. A collection of six different species of jellyfish. Attribution 4.0 International (CC BY 4.0). https://www.kaggle.com/datasets/anshtanwar/jellyfish-types
