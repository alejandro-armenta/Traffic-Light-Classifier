# Traffic Light Classifier

This is a Traffic Light Classifier that classifies lights into red, green or yellow lights.

<img width="448" alt="Input" src="https://github.com/user-attachments/assets/c312509a-08dc-493d-9898-00afc4c66292">

## Data Pre Processing

I standardized the input images and the output labels. So that I can use the same classification pipeline.

<img width="362" alt="Standardized" src="https://github.com/user-attachments/assets/22515c78-43c2-4c7c-bcc4-4596f3376cd1">

## Feature Extraction

I made a filter that counts the intensity values vertically. 

## Classifier 

Then I classify based on the index of the maximum row.
