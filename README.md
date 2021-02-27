“Every artist was first an amateur”
-Ralph Waldo Emerson
Art is not just paintings or music, but, the power to comprehend things, the power to create, is also an art. This is the type of art that ML models focus on (mostly) and what I have been doing lately. I have been working with Inception (V3) and GloVe models for the purpose of image auto-captioning. I started with GloVe to make the system understand different words, their contexts and similiarites and to get word embeddings for captions (training data). Once I had a batch generator that produced images along with their respective captions(embeddings), all that was left to train a model on this data. Inception_V3 is a pre-trained model that applies the concept of transfer learning. It consists of a CNN for feature extraction and fully-connected layers for classification. Using this model helped improve the performance of the model as it was pre-trained, so, the only thing required was to fine-tune the hyper-parameters according to the data.
