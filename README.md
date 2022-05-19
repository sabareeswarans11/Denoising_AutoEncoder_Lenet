# Denoising_AutoEncoder_Lenet
1)denoising the input digit image with random noises.
2)classifying the input digit image.

<img width="700" alt="Screenshot 2022-05-19 at 3 53 20 PM" src="https://user-images.githubusercontent.com/94094997/169392498-2114958f-aee8-4aa2-9405-6b726c7fec7a.png">

# Project Structure 
1)Main File --./Denoising_AutoEncoder_Lenet/denoising_AutoEncoder.ipynb
2)Custom Test Directory --./Denoising_AutoEncoder_Lenet/Encoder_Input (it contains the 4 images need to test and denoise)
3)Pre-Trained Model --./Denoising_AutoEncoder_Lenet/lenet_encoder_sab.pth

# DataSet
MNIST Dataset -Downloaded from Torchvision-PyTorch

# Lenet Architecture and hyperparameters
<img width="500" alt="image" src="https://user-images.githubusercontent.com/94094997/169392850-5f570d57-f15b-4f40-abe5-49b53b21616a.png">

1)Multi_Optimizer – Adam and SGD for better results
2)Loss Function – L1 Loss for denoising
3)Used Square0 to add noise to the TrainSetTensor 

# Loss Curve 
<img width="600" alt="image" src="https://user-images.githubusercontent.com/94094997/169393374-dc08f4ed-3551-40dc-a6d1-33dce2d5d45e.png">

# Network Input and Output Results

<img width="700" alt="image" src="https://user-images.githubusercontent.com/94094997/169393587-b559c379-c6ff-4da9-91bc-b2287e9e40b2.png">
<img width="700" alt="image" src="https://user-images.githubusercontent.com/94094997/169393671-682df629-29d7-4ee5-bdd9-81f906acd7f8.png">
