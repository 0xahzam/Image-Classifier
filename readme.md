# Image Classification using CLIP

This is a self contained notebook using `openai/CLIP` to classify images from dataset of images inside a folder using a `token` and group them in another folder where name of folder having `token` as the folder name.

For example, if `token = "a bike"` then all the images resembling the token, a bike, will be classified and grouped into a new folder in the parent directory named "a bike".

### Folder Structure before running the script:
- Parent Directory
  - classify.ipynb
  - images
    - car.png
    - bike.png
    - bike2.png

### Folder Structure after running the script:
here `token = "a bike"`

- Parent Directory
  - classify.ipynb
  - bike
    - bike.png
    - bike2.png
  - images
    - car.png
