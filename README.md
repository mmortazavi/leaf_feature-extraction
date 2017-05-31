# Leaf Feature Extraction

A simple approach to extract features using quasi time-series (based on leaf's outermost contours) and similarity distances using Dynamic Time Wrapping (DTW) using Python. The motivation behind this was based on a recent competition in Kaggle: https://www.kaggle.com/c/leaf-classification. While one can argue about the usefulness of this kind of feature for constructing a robust classfication model, here the idea is to provide a padalogical introduction to time series (or quasi time series) and  smart Dynamic Time Wrapping apprach for identifing identical ones.

First the outermost contour of a leaf is found, and subsequently a corressponding quasi time series is constructed. Further the distances between time series are measured using standard Dynamic Time Wrapping as implemented in mlpy - Machine Learning Python see: http://mlpy.sourceforge.net/.

Required Python libraries and packages:

- python3.5
- pandas
- numpy
- seaborn
- matplotlib
- scipy
- skimage # Python image processing library: http://scikit-image.org/
- mlpy    # Machine Learning Python library: http://mlpy.sourceforge.net

Once all requirements are met, just run the Feature_Extraction_Leaf_Dynamic_Time_Wrapping.ipynb
P.S.: Full list of images can be found in the offical link of the competition in Kaggle website. Here only I am listing the first 100 images to demonstrate the DTW technique for measuring similarity between time series.
