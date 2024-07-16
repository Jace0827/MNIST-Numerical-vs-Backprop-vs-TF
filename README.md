# NN-Numerical-vs-Backprop-vs-TF

This project demonstrates two methods of training a neural network using the MNIST dataset: numerical differentiation and backpropagation. It includes the implementation of both methods, allowing users to switch between them and observe the differences in training efficiency and accuracy.

## Getting Started

### Preparing the MNIST Data

You need to download the MNIST dataset manually and place the files in the same directory as this project. 

Download the dataset from [here](https://www.kaggle.com/datasets/oddrationale/mnist-in-csv?select=mnist_train.csv).

Download the following files:
- `mnist_train.csv`
- `mnist_test.csv`

Extract the files and place them in the same directory as this project.

Once the files are placed correctly, you can run the project.



# Result:

## Numerical

![image](https://github.com/Jace0827/NN-Numerical-vs-Backprop/assets/128456403/4141d307-5146-40ba-b3bc-ffe7d3c3cb73)

![image](https://github.com/Jace0827/NN-Numerical-vs-Backprop/assets/128456403/b6235db4-6b81-440d-ac07-60bbe4b89f46)

## Backprop

![image](https://github.com/Jace0827/NN-Numerical-vs-Backprop/assets/128456403/4651e2a3-57d2-4b32-a23c-12efe8f6bc3c)

![image](https://github.com/Jace0827/NN-Numerical-vs-Backprop/assets/128456403/c2662403-ae15-44b6-9ce7-5ee25daea569)

## TF

![image](https://github.com/user-attachments/assets/272d899d-e48e-493a-a132-354cc9fd9d8a)

![image](https://github.com/user-attachments/assets/87e55d0c-ad7e-4728-8f1d-6646ced69bab)

![image](https://github.com/user-attachments/assets/1fcce947-94cb-4ca1-aad8-207df6c64e9b)

![image](https://github.com/user-attachments/assets/b416ad8a-f2c2-4a2a-8b3e-c17354308782)

# Conclusion

## Overfitting Observation
After performing more than two epochs, overfitting was observed. This indicates that while the model performed well on the training data, its performance on the validation or test data did not improve, and in some cases, it worsened.

## TensorFlow Training Efficiency
In training using TensorFlow, each epoch took approximately 1 second. This efficiency is attributed to TensorFlow's backend, which is implemented in C++ and is optimized for performance. TensorFlow utilizes highly optimized libraries for matrix operations and can leverage GPU acceleration, significantly speeding up the training process.
