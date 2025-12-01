## Problem Description
The goal of this problem is to identify metastatic tissue in histopathologic scans of lymph node sections. Given images of scans the goal is to identify the scans as positive or negative.

The images have dimension 96x96x3 which is about 27,648 predictors for each image. There are a total of about 220,000 train images with known labels and 57,458 test images.

Given the limitations of using the free version of Google Colab and Google Drive, we limit the train dataset size for modeling below to 20,000 train images to allow for quicker model tuning and optimization.

Kaggle: https://www.kaggle.com/c/histopathologic-cancer-detection/overview
