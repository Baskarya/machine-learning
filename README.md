# Machine Learning Baskarya

## Description
Machine learning make recomendation system based by visual similarity.

## Method
Created machine learning model for batik motif classification using a pre trained model from MobileNetV2. Then we take the layer before the output layer to extract images from each batik and look for similarities using cosine similarity to make recommendations.

## Tools
- [![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)](https://www.python.org/)
- [![TensorFlow](https://img.shields.io/badge/TensorFlow-FF6F00?style=for-the-badge&logo=tensorflow&logoColor=white)](https://www.tensorflow.org/)
- [![Numpy](https://img.shields.io/badge/Numpy-013243?style=for-the-badge&logo=numpy&logoColor=white)](https://numpy.org/)
- [![Scikit-Learn](https://img.shields.io/badge/Scikit_Learn-F7931E?style=for-the-badge&logo=scikit-learn&logoColor=white)](https://scikit-learn.org/)
- [![Pillow](https://img.shields.io/badge/Pillow-8B008B?style=for-the-badge&logo=pillow&logoColor=white)](https://python-pillow.org/)
- [![Matplotlib](https://img.shields.io/badge/Matplotlib-3776AB?style=for-the-badge&logo=matplotlib&logoColor=white)](https://matplotlib.org/)
- [![Jupyter Notebook](https://img.shields.io/badge/Jupyter_Notebook-F37626?style=for-the-badge&logo=jupyter&logoColor=white)](https://jupyter.org/)

## Dataset
This dataset is a collection of images collected from various sources.

### Sources
- [Indonesian Batik Motifs](https://www.kaggle.com/datasets/dionisiusdh/indonesian-batik-motifs)
- [Indonesian Batik Motifs (Corak App)](https://www.kaggle.com/datasets/alfanme/indonesian-batik-motifs-corak-app/data)
- [Dataset-Motif-Batik](https://github.com/arifnurrhmnn/Dataset-Motif-Batik/tree/master)
- [Google Images](https://images.google.com/)

### Data Preparation
The process of preparing the dataset involved:

1. **Collection:** Gathering images from multiple sources, ensuring a wide range of samples.
   
2. **Selection:** Choosing images based on quality, relevance, and adherence to project criteria.

3. **Combination:** Merging selected images into a cohesive dataset.

### Dataset Result : [Dataset](https://github.com/putramkti/baskarya-machine-learning/tree/main/dataset)


## Deployment
We using Flask to deploy machine learning model. [Click here](https://github.com/Baskarya/flask-ml-model) to see documentation.


## Reference
- [Medium Article: "Image-Based Product Recommendation System"](https://zakim.medium.com/image-based-product-recommendation-e1bfa29e508)
- 
