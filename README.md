<p align="center">
  <a href="https://www.perceptilabs.com">
  <img src="./pl_logo.png">
  </a>
</p>

# Chest X-Ray Dataset
This dataset<sup>1</sup> contains 224x224-pixel images of chest x-rays.

The data can be used to build and train an ML model that can detect pneumonia. 

# Structure
This repo has the following structure:
* **/img**: contains the chest x-ray images.
* **/data_1.csv**: CSV file that enumerates the images for use in loading the data into PerceptiLabs. The enumerations are: normal=0, infected=1.

The following shows a partial example of the data stored in the CSV file:

| image_path | target |
| ---------- | ------ |
| img/chest_0.jpeg | 0 |
| img/chest_virus_107.jpeg | 1 |


# Community

Got questions, feedback, or want to join a community of machine learning practitioners working with exciting tools and projects? Check out our [Community](https://forum.perceptilabs.com/)!

<sup>1</sup> Dataset Credits: https://www.kaggle.com/paultimothymooney/chest-xray-pneumonia
