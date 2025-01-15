# LFASR-BP
Light Field Reconstruction using Pixel Shuffle based on Back-Projection Network

In this paper, we propose a new light field(LF) reconstruction network that increases LF angular resolution. The proposed method consists of two parts that extracts the initial feature map and refines the extracted initial feature map. In order to efficiently extract features from input images, we rearrange the input images into a macro-pixel image using pixel shuffle and then extract the initial feature map using successive convolution layers. The refinement network continuously extracts inherent correlation information using a dense back-projection structure. Finally, we are able to stably train the network and reconstruct high-quality LF images by connecting the initial feature map and the output of the refinement network with long skip connection. Simulation results show that the proposed network outperforms other existing methods in terms of execution time and reconstructed LF image quality.

## Requirements
- Python 3.9
- PyTorch 1.13

## Dataset
The test dataset can be downloaded at:

https://drive.google.com/drive/folders/1HgdVvhTBcHkH0getbNebHWaQZGX92mzc?usp=sharing
and save the test dataset files to "TestData" folder.

## Test
The trained model can be downloaded at:

https://drive.google.com/file/d/1mXp_PJKDhXPR0287FEHgPcQywti87a7U/view?usp=sharing
and save the pretrained model to "Model" folder.
