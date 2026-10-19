::: {align="center"}
# 🧠 Deep Learning 

### Five mini-projects in Neural Networks, Computer Vision & NLP

**ANN · OpenCV · CNN · RNN/LSTM · Transformers**

![Python](https://img.shields.io/badge/Python-3.x-3776AB?style=for-the-badge&logo=python&logoColor=white)
![TensorFlow](https://img.shields.io/badge/TensorFlow-Keras-FF6F00?style=for-the-badge&logo=tensorflow&logoColor=white)
![OpenCV](https://img.shields.io/badge/OpenCV-Image%20Processing-5C3EE8?style=for-the-badge&logo=opencv&logoColor=white)
![Hugging
Face](https://img.shields.io/badge/Hugging%20Face-Transformers-FFD21E?style=for-the-badge&logo=huggingface&logoColor=black)
![Status](https://img.shields.io/badge/Status-Practical%20Completed-success?style=for-the-badge)

*A beginner-friendly collection of practical deep learning experiments,
evaluations, visualizations, and saved models.*
:::

------------------------------------------------------------------------

## 📌 Project Overview

This repository contains the **Deep Learning Practical Exam --- Set B**.
It demonstrates five core workflows: tabular classification with an
Artificial Neural Network (ANN), image preprocessing with OpenCV, image
classification with a Convolutional Neural Network (CNN), review
classification with an LSTM-based Recurrent Neural Network (RNN), and
pre-trained Transformer pipelines for sentiment analysis and Named
Entity Recognition (NER).

The main notebook is designed to show the workflow step by step,
including data preparation, model building or pipeline setup,
evaluation, visualizations, and reflections.

## 🗂️ Tasks Covered

  -------------------------------------------------------------------------
  Step              Topic              Dataset / Input   Main Work
  ----------------- ------------------ ----------------- ------------------
  1                 **ANN --- Cancer   Breast Cancer     Standardization,
                    Classification**   Wisconsin dataset ANN with Dropout,
                                       --- 569 rows, 30  training curves,
                                       features          accuracy,
                                                         precision, recall,
                                                         F1-score and
                                                         confusion matrix

  2                 **OpenCV --- Image 5 images: apple,  Resize, grayscale,
                    Processing**       banana, flower,   median blur, Otsu
                                       cat and car       thresholding,
                                                         contours, colour
                                                         histogram, flip
                                                         and rotate

  3                 **CNN --- Fashion  Fashion-MNIST --- CNN training,
                    Classification**   20,000 training   accuracy/loss
                                       and 4,000 test    curves,
                                       images used       classification
                                                         report, confusion
                                                         matrix and sample
                                                         predictions

  4                 **RNN/LSTM ---     IMDB --- 10,000   Token sequences,
                    Review             training and      padding,
                    Classification**   5,000 test        Embedding, LSTM,
                                       reviews used      evaluation and
                                                         review predictions

  5                 **Transformers --- 20 custom product Hugging Face
                    NLP**              reviews and 5 NER sentiment
                                       sentences         pipeline,
                                                         tokenization,
                                                         confidence scores,
                                                         bar chart and
                                                         entity recognition
  -------------------------------------------------------------------------

## 📊 Results Summary

The values below are taken from the executed notebook outputs.

  ------------------------------------------------------------------------
  Task                  Metric                                      Result
  --------------------- --------------------- ----------------------------
  ANN --- Breast Cancer Test accuracy                           **97.37%**

  OpenCV --- Image      Accuracy                   **N/A --- preprocessing
  Processing                                                        task**

  CNN --- Fashion-MNIST Test accuracy                           **88.60%**

  RNN/LSTM --- IMDB     Test accuracy                           **80.98%**

  Transformer ---       Correct among 16                  **16/16 (100%)**
  Sentiment Analysis    clearly               
                        positive/negative     
                        reviews               
  ------------------------------------------------------------------------

> **Note:** The Transformer result is the manually checked result for
> the 16 clearly positive/negative reviews in this small custom sample.
> It is not a benchmark on a large independent test dataset; the four
> mixed/neutral reviews are discussed separately. Model performance can
> vary with data and environment.

## 🧰 Tools & Technologies

-   **Language:** Python
-   **Deep Learning:** TensorFlow, Keras
-   **Computer Vision:** OpenCV, Matplotlib
-   **Data Analysis:** NumPy, Pandas, Seaborn
-   **Machine Learning utilities:** scikit-learn
-   **NLP:** Hugging Face Transformers, PyTorch
-   **Notebook:** Jupyter Notebook / Google Colab

## 📁 Repository Structure

``` text
deep-learning-practical-exam-set-b/
├── DeepLearning_Practical_Exam_SetB.ipynb
├── ann_cancer_model.h5
├── cnn_fashion_model.h5
├── rnn_imdb_model.h5
├── outputs/
│   ├── original and preprocessed images
│   └── saved plots / visualizations (if included)
├── summary_report.md
├── requirements.txt
└── README.md
```

Keep the filenames in your repository consistent with the names listed
above. The `outputs/` folder should contain the actual
original/preprocessed OpenCV images generated by the notebook.

## 📦 Saved Models

  -----------------------------------------------------------------------
  File                                Purpose
  ----------------------------------- -----------------------------------
  `ann_cancer_model.h5`               Trained ANN for breast cancer
                                      classification

  `cnn_fashion_model.h5`              Trained CNN for Fashion-MNIST image
                                      classification

  `rnn_imdb_model.h5`                 Trained LSTM/RNN for IMDB sentiment
                                      classification
  -----------------------------------------------------------------------

These files should be uploaded after they have been saved successfully
by the notebook.

## 🎥 Project Demonstration Video

**Video link:** `Add your Google Drive or unlisted YouTube link here`


## 🔮 Future Improvements

-   Tune model architectures and hyperparameters and compare validation
    results.
-   Add more robust image handling and save all requested outputs
    consistently.
-   Test sentiment analysis on a larger set of Indian-English, Hinglish
    and regional-language reviews.
-   Evaluate the models on independent data and document limitations.
-   Build a secure API for sentiment inference with input validation,
    monitoring and deployment.

## 👩‍💻 Author

**Janki Dholariya**\
AI/ML & Data Science Student
