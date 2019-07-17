# DynamicUnet
This project is the "error-free" implementation of Dynamic U-Net architecture on Caravan Mask Challenge Dataset. A state of the art technique that has won many Kaggle competitions and is widely used in industry. Image segmentation models allow us to precisely classify every part of an image, right down to pixel level.
This code will be useful for anykind of binary instance classification.

## Getting Started

For quick experiments, you can use Google Colab using [caravan-work.ipynb](https://colab.research.google.com/github/ashutoshraj/DynamicUnet/blob/master/caravan-work.ipynb) You can also run the experiments locally.

### Requirements

#### For running locally
-   Install PyTorch (pytorch.org)
-   Install [Fastai](https://docs.fast.ai/install.html)
-   Download the data from [here](https://www.kaggle.com/c/carvana-image-masking-challenge/data)

#### For running in Colab
-   Everything is already installed
-   To download the data from [here](https://www.kaggle.com/c/carvana-image-masking-challenge/data) to your Colab VM, you can use CurlWget Chrome Extension
    -   Note: You should keep a copy of the data in your Google Drive for later use.

## Acknowledgments

-   [U-Net: Convolutional Networks for Biomedical Image Segmentation](https://arxiv.org/abs/1505.04597) by Olaf Ronneberger, et al.

-   [Practical Deep Learning for Coders, v3](https://course.fast.ai/)

-   [Fast AI Forum](https://forums.fast.ai/)

## Contributing
Pull requests are welcome. For major changes, please open an issue first to discuss what you would like to change.

Please make sure to update tests as appropriate.

## License
[MIT](https://choosealicense.com/licenses/mit/)
