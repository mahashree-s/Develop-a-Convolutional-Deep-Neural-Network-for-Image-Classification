# Develop a Convolutional Deep Neural Network for Image Classification

## AIM
To develop a convolutional deep neural network (CNN) for image classification and to verify the response for new images.

##   PROBLEM STATEMENT AND DATASET
To classify images of clothing into different categories using a Convolutional Neural Network. 
The CNN learns image features through convolution and pooling layers and predicts the correct clothing category.

Dataset: Fashion-MNIST
- Dataset: Fashion-MNIST
- Training images: 60,000
- Testing images: 10,000
- Image size: 28 × 28 pixels
- Image type: Grayscale
- Number of classes: 10
  
Classes:
1. T-shirt/top
2. Trouser
3. Pullover
4. Dress
5. Coat
6. Sandal
7. Shirt
8. Sneaker
9. Bag
10. Ankle boot

    
## Neural Network Model
<img width="3840" height="1461" alt="image" src="https://github.com/user-attachments/assets/ab73f6b0-e579-4ab3-856e-b252333e8c32" />

## DESIGN STEPS
STEP 1: Import the required libraries such as PyTorch, Torchvision, NumPy, Matplotlib and Scikit-learn.

STEP 2: Load the Fashion-MNIST dataset and apply image transformations such as tensor conversion and normalization.

STEP 3: Divide the dataset into training and testing sets and create DataLoaders.

STEP 4: Design the CNN model using convolutional, ReLU, max-pooling and fully connected layers.

STEP 5: Initialize the model, loss function and Adam optimizer. Train the model for three epochs.

STEP 6: Evaluate the model using accuracy, confusion matrix and classification report. Predict the class of a new sample image.





## PROGRAM

### Name: MAHASHREE S

### Register Number: 212225230163

```python
class CNNClassifier(nn.Module):
    def __init__(self, input_size):
        super(CNNClassifier, self).__init__()
        #Include your code here

    def forward(self, x):
        #Include your code here



# Initialize the Model, Loss Function, and Optimizer
model =
criterion =
optimizer =

# Train the Model
def train_model(model, train_loader, num_epochs=3):

    # write your code here

        
        
        
        print('Name:        ')
        print('Register Number:       ')
        print(f'Epoch [{epoch+1}/{num_epochs}], Loss: {running_loss/len(train_loader):.4f}')

```

### OUTPUT

## Training Loss per Epoch

Include the Training Loss per epoch

## Confusion Matrix

Include confusion matrix here

## Classification Report
Include classification report here

### New Sample Data Prediction
Include your sample input and output here

## RESULT
Include your result here
