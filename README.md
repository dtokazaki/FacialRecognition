Facial Recognition Bot that find the % acurracy on the subspaces of rank K=1,2,3,6,10,20, and 30.

Using a training database of 60 images, and a testing database of 40 images, performed singular value decomposition to create a model and compared every image of the testing set with the model. Correct guesses for each K'th rank were added up to calculate a percent acuuracy for each K'th rank.
Run faceRec.py using Python 3.4, NumPy 1.13.3, and cv2 3.4.3.The image databse is stored in the att_faces_10 folder.


