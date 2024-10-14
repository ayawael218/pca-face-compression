# pca-face-compression
1) Description:
   This project implements Principal Component Analysis (PCA) for face reconstruction using the Labeled Faces in the Wild (LFW) dataset, demonstrating dimensionality reduction and image compression techniques.

2) Key Features:
  Dataset Utilization: Loads the LFW dataset with a minimum of 70 faces per person, resulting in 1288 samples and 1850 features across 7 classes.
  Data Preprocessing: Centers the data by subtracting the mean and computes the covariance matrix.
  Eigenvalue Decomposition: Extracts principal components by calculating eigenvectors and eigenvalues, selecting the top 50 for dimensionality reduction.
  Image Reconstruction: Projects the centered data onto the principal components and reconstructs the original images, enabling visualization of compressed and decompressed faces.

3) Programming Tools:
    Python, NumPy, Scikit-learn, Matplotlib.
