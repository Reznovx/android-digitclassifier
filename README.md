# Data Mining Project
<h2 align="center">
Aplikasi Tulisan Tangan Digit Classifier<br/>
</h2>
<hr>


<a name="general-information"></a>

## General Information
A straightforward website utilizing one of the concepts of deep learning, Convolutional Neural Networks (CNN), to analyze diseases in potato plants. The program utilizes a dataset from Kaggle, specifically the [Plant Village dataset](https://www.kaggle.com/datasets/arjuntejaswi/plant-village), to construct the model. The model deployed in this application achieves a confidence score exceeding 98%, with a margin of error of 1.5%. It is hoped that this application will assist farmers in identifying diseases in their potato plants early, enabling them to address the issue promptly.

<a name="creator-information"></a>

## Member
| Nama                  | NIM          | E-Mail                 |
| --------------------- | ------------ | ---------------------- |
| Alfareza K Deva M     | 20214350xxxx | alfar2801@gmail.com    |
| Reza Khareisa Putra   | 202143502344 | rezakhareisa@gmail.com |

<a name="features"></a>

## Features
- Read `input` as an image
- User could `drag and drop` their picture or just `click the upload button` 

<a name="technologies-used"></a>

## Technologies Used
- Android SDK - API Level 34 (Android 14)
- Kotlin - v1.9.23
- Gradle (Build) - v8.2.0
- Gradle (Wrapper) - v8.8
- TensorFlow - v2.15.0
- TensorFlow Lite - v2.5.0

<a name="goals"></a>

## Goals
- How to train a handwritten digit classifier model using TensorFlow
- How to convert a TensorFlow model to TensorFlow Lite
- How to deploy a TensorFlow Lite model to an Android app

<a name="requirements"></a>

## Requirements
- Google Colab
- Android Studio (versi terbaru)
- Android Emulator atau Android device
- Basic Pemrograman Kotlin untuk Android


<a name="setup"></a>

## Setup
1. Install Android Studio (jika belum)
2. Clone repository ini menggunakan command berikut:
    ```bash
    git clone https://github.com/Reznovx/android-digitclassifier.git
    ```
    - atau download langsung melalui tombol `<> Code` -> `Download ZIP` diatas
4. Buka Android Studio
5. Klik `Import project`
6. Pilih folder `android-digitclassifier` pada direktori yang dimana folder tersebut di extract 
7. Tunggu hingga proses import selesai


<a name="usage"></a>

## Usage
1. To run the backend, you can use the following steps:
    - go to `api` folder
    - run this command in your terminal
    ```bash
    uvicorn main-tf-serving:app --reload --host 0.0.0.0
    ```
    - or just type
    ```bash
    python main.py
    ```
3. After that, run the frontend by following this steps:
    - go to `frontend` folder
    - run this command in your terminal
    ```bash
    npm run start
    ```
    
<a name="videocapture"></a>

## Video Capture
<nl>

![android-app-demo Gif](https://github.com/Reznovx/android-digitclassifier/blob/main/app/src/main/assets/android-app-demo.gif?raw=true)

<a name="project-status">

## Project Status
_Complete_

<a name="room-for-improvement">

## Room for Improvement
Room for Improvement:
- Optimizing the model accuracy with other layering approach

<a name="acknowledgements">

## Acknowledgements
- Thanks To Allah SWT
<hr>
