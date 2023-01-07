# Eye For Blind
To create a deep learning model that can explain the content of an image in the form of speech through caption generation. 

Model used: 
This problem statement is an application of both deep learning and natural language processing. The features of an image will be extracted by the CNN-based encoder, and this will be decoded by an RNN model.

Model Building Pipeline: 
- Data understanding: Load data and understand basic visualizations. 
- Data preprocessing: Process both images and captions in the desired format.
- Train/Test split: Combine both images and captions to create the train and test data sets.
- Model building: Create image captioning model by building the Encoder, Attention and Decoder model
- Model evaluation: Evaluate the models using greedy search and the BLEU score.

References: 
"Xu, Kelvin and Ba, Jimmy and Kiros, Ryan and Cho, Kyunghyun and Courville, Aaron and Salakhutdinov, Ruslan and Zemel, Richard and Bengio, Yoshua" - Show, Attend and Tell: Neural Image Caption Generation with Visual Attention
