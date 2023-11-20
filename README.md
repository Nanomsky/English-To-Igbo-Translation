# English-To-Igbo-Translation
English translation to Igbo using TensorFlow Transformer model. 

## Table of contents
* [General info](#general-info)
* [Technologies](#technologies)
* [Data](#data)

# General Info
This NLP project applies the Tensorflow Transformer model in a sequence-to-sequence modelling task. Sports headlines published in English language are translated into Igbo language using the transformer model and the results are compared to the published Igbo version. <a href='https://en.wikipedia.org/wiki/Igbo_language'>Igbo</a> is the native language spoken by people from the south eastern part of Nigeria. It is spoken by over 31 million people.

# Technologies
Project was created with:

* Python==3.8.18
* TensorFlow==2.13.0
* Keras==2.13.1

## Data
The data, made up of headlines of sports news, was scrapped from the Complete Sports <a href='https://www.completesports.com/'>English</a> and <a href='https://www.completesports.com/ig/'>Igbo</a> websites. The 17963 English-Igbo pairs was split into training(80%), validation(10%) and test(10%) datasets.
