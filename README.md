# Traffic Light Classifier

This is a Traffic Light Classifier that classifies lights into red, green or yellow lights.

<img width="448" alt="Input" src="https://github.com/user-attachments/assets/c312509a-08dc-493d-9898-00afc4c66292">

## Data Pre Processing

I standardized the input images and the output labels. So that I can use the same classification pipeline.

<img width="362" alt="Standardized" src="https://github.com/user-attachments/assets/22515c78-43c2-4c7c-bcc4-4596f3376cd1">

## Feature Extraction

I made an histogram of frequencies of intensity values for each row in the image. Cropped and masked obviuously.

<img width="590" alt="HSV" src="https://github.com/user-attachments/assets/6336eeff-9294-4c59-b00f-166095a6b309">

## Classifier 

Then I classified the images using the histogram of frequencies.
