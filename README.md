# Neural Network Fundamentals and Training Behavior Analysis

## Project Overview

This project focuses on building and analyzing a feed-forward neural network model for customer churn prediction.

The objective is to understand how neural networks learn through:
- Forward propagation
- Loss calculation
- Backpropagation
- Parameter updates
The project also includes hyperparameter experimentation and performance analysis.

## Dataset Source

Dataset provided in the assignment shared Google Drive folder:
https://drive.google.com/drive/folders/1akV6po4Nrgkc3yQrJkzA6cJlV-wBvUYs?usp=sharing

## Dataset Information

Dataset: Customer Churn Neural Network Dataset
Target Variable:
- `churn`
    - 1 = Customer churned
    - 0 = Customer retained

Features include:
- Customer region
- Plan type
- Contract type
- Payment method
- Tenure
- Charges
- Login activity
- Support tickets
- Data usage
- Satisfaction score
- Referral count

`customer_id` was removed because it is only an identifier.

## Steps Performed

### 1. Dataset Understanding
- Checked dataset shape
- Analyzed feature types
- Verified missing values
- Generated statistical summary
- Visualized target distribution

### 2. Data Preprocessing
- Removed unnecessary columns
- Encoded categorical variables
- Scaled numerical features
- Performed train-test split

### 3. Neural Network Model Building
- Built a feed-forward neural network
- Used ReLU activation for hidden layers
- Used Sigmoid activation for output layer
- Used Binary Crossentropy loss function
- Used Adam optimizer

### 4. Training and Evaluation
- Trained the neural network model
- Evaluated model performance
- Generated confusion matrix
- Compared training and validation accuracy

### 5. Hyperparameter Experimentation
Three different neural network configurations were tested by changing:
- Number of hidden layers
- Number of neurons
- Learning rate
- Batch size
- Number of epochs

## Results

The neural network model achieved good prediction accuracy on the customer churn dataset.
Hyperparameter experimentation showed that model architecture and learning rate significantly affect performance.

## Conclusion

This project helped in understanding the working of neural networks and the importance of:
- Feature preprocessing
- Activation functions
- Hyperparameter tuning
- Model evaluation

The experiments demonstrated how neural networks improve learning through weight updates and optimization.