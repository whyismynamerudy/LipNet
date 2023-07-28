# LipNet
 
 A neural network capable of decoding text from the movements of a speaker's mouth ("lip reading"). This end-to-end sentence-level lip reading model was trained using a subset of the data used in the paper [https://arxiv.org/abs/1611.01599](https://arxiv.org/abs/1611.01599). 
 
 The structure of the neural network follows the structure described in the paper, except it substitutes the Bi-GRU model with a Bi-LSTM model. 
 As detailed in the paper, this model also uses a CTC loss function (sourced from the Keras documentation). 
 
 The end weights (obtained after 96 epochs) were loaded in from an external source due to computational limitations on my local machine :(. 
