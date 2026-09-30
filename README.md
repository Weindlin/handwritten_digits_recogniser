# Handwritten Digit Recognizer (IDPA Project)

This repository contains the code and documentation for my IDPA (Interdisciplinary Project Work) project. The goal of this project was to build and train a Convolutional Neural Network (CNN) capable of accurately recognizing handwritten digits.

## Live Demo

You can test the EMNIST-trained model yourself directly in your browser using Hugging Face Spaces:
👉 [**Try the EMNIST Model on Hugging Face**](https://huggingface.co/spaces/Weindlin/IDPA_Handwritten_Digits_recogniser)

## Project Overview

In this project, I developed two separate CNN models to tackle the task of handwritten digit recognition. The models were trained and evaluated using two well-known datasets:

1. **MNIST Dataset:** The classic dataset consisting of 60,000 training images and 10,000 testing images of handwritten digits (0-9).

2. **EMNIST Dataset (Extended MNIST):** An extended dataset consisting of 240,000 training images and 40,000 testing images of handwritten digits & letters, providing more variety to improve the model's robustness and generalization.

### Real-World Testing

To ensure the models didn't just memorize the datasets, I created a custom dataset by writing digits myself. This allowed me to test the models' performance on completely unseen, real-world data and compare how well both the MNIST and EMNIST models generalized to everyday handwriting.

## Technologies Used

* Python

* Convolutional Neural Networks (CNN)

* Machine Learning Framework (TensorFlow)

* Hugging Face Spaces (for deployment)

## License

This project was created as part of an IDPA. Feel free to explore the code and reach out if you have any questions!
