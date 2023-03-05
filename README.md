Domain: Deep learning
Topic: Human Face Recognition Using Computer Vision

Human face recognition is a popular area of computer vision that involves identifying and verifying individuals based on their facial features from digital images or video frames.
The first step in building a face recognition system is to collect a dataset of images of individuals and extract their facial features. This can be done using various algorithms such as LBP, HOG, or CNN.
Next is the process of face alignment, so that the detected faces are in a standardized position and scale. This is important because different images may have faces in different orientations and sizes. Face alignment can be achieved by using facial landmark detection or face normalization techniques. 
Finally, the step of face recognition involves using a face detection algorithm to match the detected face with the database of individuals to identify the person. There are various face recognition algorithms available, such as Eigenfaces, Fisherfaces, and Local Binary Patterns Histograms (LBPH). These algorithms extract features from the face, such as texture, shape, and color, and use machine learning techniques to learn a model that can recognize the person.
The proposed approach mainly focusses on the use of libraries Face Recognition and OpenCV based on the SVM model and LBPH algorithm. dlib and numpy packages are required to use the mentioned libraries. 
HOG algorithm is used for face detection. The database is enhanced by capturing different angles of the same individual. The face embedding is a compact and robust representation in the form of 128 measurements of the face that captures its unique characteristics, such as the shape, texture, and color of the facial features.
The face embeddings of the faces in the database are computed in advance, and when a new face is presented, its face embedding is computed and compared with the embeddings in the database using a similarity metric. The face with the closest embedding is considered to be the match.
The matches are represented as a csv file which can further be used as an employee attendance system at the respective firm.


