# __Implementation of an Image Retrieval System Based on Text Descriptions and Similar Image Search in a Dataset__


## __INSTALLATION:__
You need to have Python 3 installed (preferably version 3.11).  
Run the following commands sequentially in your terminal:

1. Clone this repository:
```
git clone https://github.com/galelisette/im_retrive.git
```

2. Navigate to the project directory:
```
cd SORT-DeepSORT-Tracker
```

3. Install all required dependencies:
```
pip install -r requirements.txt
```

PS: It is recommended to install PyTorch with GPU support __if available__:
```
pip install torch torchvision torchaudio --index-url https://download.pytorch.org/whl/cu121
```

4. Run the notebook [retrival.ipynb](https://github.com/galelisette/im_retrive/blob/master/retrival.ipynb), which contains examples of image retrieval

5. Create a folder named __images__ in the root of the repository and place the images you want to analyze inside it

<br/>


PS: For image feature extraction, I recommend using this CLIP model, as it was trained on a larger dataset:  
https://huggingface.co/laion/CLIP-ViT-B-32-laion2B-s34B-b79K

***
