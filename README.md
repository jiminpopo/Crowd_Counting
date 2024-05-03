# Crowd Counting

This is my final team project for the 'Introduction to Deep Learning' class at the University of Toronto, where I was an exchange student during the winter semester of 2024 (January to April).
Here is my final report. Due to file size limitations, the final report will be uploaded in two parts.

I concentrated on using the pre-trained VGG16 model. From my experience, utilizing VGG16 alone did not yield satisfactory results, so I incorporated an ASPP module, similar to the skip-connection in U-Net, to enhance performance. Additionally, selecting the appropriate loss function is crucial. Whil U-Net performs better with BCELoss, in my work with the pre-trained VGG16, MSELoss proved to be more effective.

The file "Crowd_Counting/mywork/Jimin.ipynb" documents my experiment. Experimentally, we discovered that a smaller batch size and a larger number of epochs generally yield better results. However, in my specific experiments, setting the number of epochs to 300 proved more effective than setting it to 600.

The order of the report is as follows:

## Part 1
### 1) Introduction
### 2) Data Loading and Preprocessing
### 3) Data Visualization

## Part 2
### 4) Model and result
### 5) Quantitative Results
### 6) Qualitative Results

## Part 3
### 7) Testing on new data and demonstration
### 8) Related Works
### 9) conclusion
