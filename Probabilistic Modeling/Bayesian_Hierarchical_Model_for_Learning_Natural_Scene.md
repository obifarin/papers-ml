# Paper

-  **Title**: A Bayesian Hierarchical Model for Learning Natural Scene Categories
-  **Authors**: Li Fei-Fei, Pietro Perona
-  **Keywords**: Bayesian Model, Computer Vision
-  **Year**: 2005
-  **Link**: http://vision.stanford.edu/documents/Fei-FeiPerona2005.pdf

# Summary

**Question/Goal**: 
- The categorization of scene without the initial manual labelling of objects in the scene. 
- Previous methods had utilized a supervised intermediate representation of features locally and globally. This makes it sub-optimal given hours of manual labeling and subjectivity that might be inherent in labelling. Hence, it’s expensive, time-consuming, and potentially inefficient.

**Methods**:
- The method used include a learning phase and a recognition phase. In the learning phase, images were represented in local patches using grids, and these are in turn used to form bag of codewords. Learning is done by a Bayesian hierarchical models for each class. When presented a new image for classification; extraction of local features is carried out to form a bag of codewords, and the trained model is used for recognition. 

<img src="image/BHM_NS_algorithm.png" width=600 align="center">
