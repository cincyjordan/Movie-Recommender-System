# Matrix Factorization: Movie Recommender System

This repository includes a Jupyter Notebook that incorporates a matrix factorization technique for recommender systems, best described in the academic paper "Matrix Factorization Techniques for Recommender Systems" by Koren, Yehuda, et al. “Matrix Factorization Techniques for Recommender Systems.” Datajobs, IEEE Computer Society, 7 Aug. 2009, https://datajobs.com/data-science-repo/Recommender-Systems-%5BNetflix%5D.pdf. Accessed 7 July 2024. 

<img src='https://csdl-images.ieeecomputer.org/mags/co/2009/08/figures/mco20090800301.gif' width='800'>

In addition, this project utilizes embedding layers to represent users and movies as dense vectors. These embeddings capture latent factors from the user and item ID indices, best described in the academic paper "Neural Collaborative Filtering" by He, Xiangnan, et al. “Neural Collaborative Filtering.” arXiv, 16 Aug. 2017, https://arxiv.org/abs/1708.05031. Accessed 7 July 2024. 

<img src='https://miro.medium.com/v2/resize:fit:1400/1*aP-Mx266ExwoWZPSdHtYpA.png' width='800'>

## About

In this project, I will be using Matrix Factorization technique partnered with layer embedment to train movie recommendation system on an movie review dataset. Particularly with this model, stakeholders will be able to employ this recommender system on any movie or television streaming service such as Netflix to precisely recommend a movie based off of an end users watch history and the respected review they gave.

## Training 

- **Training:**
   - The model is trained using the Adam optimizer and MSE for the loss function.
   - Hyperparameters:
     - **Epochs**: 5
     - **Batch Size**: 4096
     - **Learning Rate**: 0.005

## Results
RMSE: 0.96
MAE: 0.71

## Getting Started
1. **Download the Movie Recommendation System Dataset:**
   - Obtain the dataset from [Kaggle](https://www.kaggle.com/datasets/vinothkumarj280204/movie-recommendation-system-dataset) and place it in the project directory.

2. **Set Up Google Colab (Optional):**
   - If using Google Colab, mount your Google Drive and store your Kaggle credentials using `google.colab.userdata`.

3. **Run the Jupyter Notebook:**
   - Open and execute the `Movie Recommender` notebook to train and evaluate the model.
  

## Acknowledgments

- Matrix Factorization Technique for Recommender Systems is based off of the published article "Matrix Factorization Techniques for Recommender Systems" by Koren, Yehuda, et al. “Matrix Factorization Techniques for Recommender Systems.” Datajobs, IEEE Computer Society, 7 Aug. 2009, https://datajobs.com/data-science-repo/Recommender-Systems-%5BNetflix%5D.pdf. Accessed 7 July 2024.
  
- User and Item Embeddings is based off of the published article "Neural Collaborative Filtering" by He, Xiangnan, et al. “Neural Collaborative Filtering.” arXiv, 16 Aug. 2017, https://arxiv.org/abs/1708.05031. Accessed 7 July 2024.
  
- The Movie Recommendation System dataset is used for training and evaluation.

