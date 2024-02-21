# Image Captioning with Pre-trained Models

This repository contains a Jupyter Notebook that demonstrates how to use a pre-trained Vision Encoder-Decoder model for image captioning. 

- Load a pre-trained model (**nlpconnect/vit-gpt2-image-captioning**)
- Prepare images for the model
- Generate captions using beam search
 - Display the original images alongside the predicted captions

## Getting Started
1. Clone the repository:

```Bash
git clone https://github.com/your-username/image-captioning-jupyter-notebook.git
```

2. Open the Jupyter Notebook:

```Bash
image-to-text.ipynb
```

3. Replace /content/air.jpg:

 - Update the list of image paths in the predict_step function to point to your own images.
 - Note: This code assumes you have access to a GPU or a CUDA-enabled environment. If not, you may need to adjust the device settings.

## Features
 - Loads and uses a pre-trained Vision Encoder-Decoder model for image captioning
 - Employs beam search for more diverse and fluent captions
 - Displays the original images along with the generated captions
 - Provides clear and concise code with comments
   
## Further Exploration
 - Experiment with different image datasets and hyperparameters
 - Try integrating this code into your own image processing workflows
 - Explore advanced model architectures for image captioning
   
## Contribution
I welcome contributions to this project! Feel free to fork the repository, make changes, and submit pull requests.

