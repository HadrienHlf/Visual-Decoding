The current folder contains all the datasets and code needed to replicate or pursue the results of my visual decoding experiments. After reading the report, you should be able to easily run the code and perform your own protocols. 

Much of my work is not featured in there, such as the dataset analysis part of the report and all the earlier versions of my models. For clarity and simplicity, I chose to only include the files needed to run the latest versions of the decoding experiments features in the report. 

To run the code, follow these steps:

1. Directly import the full folder in the home directory of your google drive.

2. Create and train a VAE to encode and decode full images or image centers by running the VAE_Image_Encoding.ipynb notebook. 

3. Create and train a model to reconstruct images or image centers from brain signals only by running the VAE_Image_Reconstruction_From_Brain.ipynb notebook. 

Note that all the models featured here are light enough so that running them using the T4 Colab GPU should not take more than a couple of minutes for 50-by-50 image centers. You should be able to get results similar to what I achieved in the report, with no modifications to the code other than choosing your desired image center size, choosing your own random seed, and possibly changing filenames. The '50 x 50 material' folder includes the results of running the code for 50-by-50 image centers, so feel free to directly use the models there for quick testing or sanity-checking.

Please reach me at hhelfgot@andrew.cmu.edu if you have any questions or want to get access to other code files. 

