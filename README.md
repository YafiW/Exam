# About the image
This is a python application which gets images and creates a PDF file in a folder called “output” with all the images printed in it.

## Build command
    docker build -t your_image_name .

## To run the image
    docker run -v $PWD/images:/app/images -v $PWD/output:/app/output my-python-image images