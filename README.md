# *Facenet*:

   # Implementation of facenet for face recognition. 
    Embedding are generated for face images such that embeddings of same person are similar while different persons are different.
    Modified ResNet function was trained using triplet loss layer plugged in and MTCNN is used for getting tightly croped face from image of person.
    as there was shortage of training data so deepfake was used to generate rest of the images of person

# *Files*:
 
    Res_Model.py : Modified ResNet model
    triplet.py   : implemetation of triplet loss function 
    faceNET.ipynb: training the model using triplet loss function
    facenet.pdf  : Research paper explaining the method
    models       : saved models
    utils        : functions required for bulding ResNet model
    MTCNN        : Multi-task Cascaded Convolutional Neural Networks for Face Detection
# *Libraries*:
    
    python     == 3.4
    Keras      == 2.10.0
    matplotlib == 3.1
    PIL        == 1.1.7 
    NumPy      == 1.19.5
    cv2        == 4.0
    sklearn    == 1.0.2
    tensorflow == 2.4.1



