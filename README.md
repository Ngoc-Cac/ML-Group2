# Machine Learning - Group2
This is a group final project on Semantic Image Segmentation using Mean Shift clustering.

Our group uses the Mean Shift implementation provided by scikit-learn to cluster pixels of images represented in RGB and HSV. We evaluate the clustering result using Silhouette Score to estimate the clustering quality. For more detailed information, we also do comparision across different clustering models using different colour models mentioned with Rand Index.\
The result shows that Mean Shift clustering shows little difference between RGB and HSV. However, the algorithm has difficulties giving accurate segmentation for images with rough textures, producing noisy clustering results.\
For purpose of bettering the clustering results, we also try a cluster merging technique using RAGs. However, we still have troubles defining an accurate and efficient threshold for merging similar nodes (clusters) in RAGs.

The source is provided in ML-Group2/main.ipynb. Before running, you need to have these libraries installed:
- [NumPy](https://numpy.org/)
- [pandas](https://pandas.pydata.org/)
- [Matplotlib](https://matplotlib.org/)
- [scikit-learn](https://scikit-learn.org/stable/)
- [scikit-image](https://scikit-image.org/)

---
### Acknowledgements
---
We would like to show many gratitudes to Dr. Nguyen An Te for guiding us through our journey with Machine Learning. It has not been an easy journey for myself, but without your wonderful guidance, I would not have learn such vital knowledge.\
We also would not be able to research and apply the knowledge you have passed down on interesting topics such as image segmentation. We wish you the best in all of your future endeavours!

---
### Our Contributors
---
Dương Gia Bảo\
Nguyễn Tấn Gia Bảo\
Trịnh Ngọc Các\
Nguyễn Thị Ngọc Diệp