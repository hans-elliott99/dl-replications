# dl-replications
Replications & offshoots of deep learning papers

`image_captioning/`  
- `models/`  
    - `ShowAttendTell` - Xu et al. (2016) use a deep ConvNet (they use Oxford VGGNet) to encode an image and use a recurrent net as a decoder. An attention model uses the image encoding and the recurrent net's hidden state to produce attention scores, which 'tell' the decoder which part of the image encoding it should attend to during each timestep. 