# Language Translation using Optical Character Recognition

You can create many interesting and useful computer vision application once you know how to perform Text Detection and Recognition on images. We will build a simple but useful application that allows you to translate text from one language to a language of your choice. This is particularly useful for tourists going to a country where the local language is very different from their country. Just take a picture of the text you don't understand and the app would tell you what's written!

For the language translation part, we will be using a library called [**googletrans**](https://pypi.org/project/googletrans/) (specifically v4), which uses the Google Translate API under the hood. The **`googletrans`** supports automatic detection of input language and translation to multiple languages.

You may also use the [Official Google Translate API](https://cloud.google.com/translate), but that would require additional setup. We wanted to introduce you to this exciting application with minimal hassle and thus we're using the googletrans package.

We have also created a streamlit app for this use case that you can try out.

## Googletrans Library and Documentation

[**`googletrans()`**](https://py-googletrans.readthedocs.io/en/latest/)

[**`googletrans.Translator()`**](https://py-googletrans.readthedocs.io/en/latest/#googletrans.Translator)
<hr style="border:none; height: 4px; background-color:#D3D3D3" />

## DB based text detection deep learning neural network
For the text detection in the image, we will be using the DB based text detection deep learning neural network model covered in the previous notebook. 

[**`DB Text Detection Model()`**](https://docs.opencv.org/master/db/d0f/classcv_1_1dnn_1_1TextDetectionModel__DB.html)

## Sample ouput 
<img width="954" alt="Screen Shot 2022-01-19 at 11 15 24 PM" src="https://user-images.githubusercontent.com/42128166/150291056-61d1b71e-7a2d-4776-b749-4d69417e8e57.png">
