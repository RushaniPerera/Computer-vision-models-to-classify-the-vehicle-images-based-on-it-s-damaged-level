# Computer vision models to classify the vehicle images based on it's damaged level

This project focus on classifying damaged vehicle images based on their damaged severity. 

<img width="606" height="252" alt="Screenshot 2025-08-07 at 3 34 50 PM" src="https://github.com/user-attachments/assets/9744eece-34a3-44d2-82f6-ffbdd6769602" />

**Four classes of the dataset is defined as follows** 

• Low- Vehicles with very minute damages like scratches, small crushes.
• Medium – Vehicles with damages to parts like shutters, metal body, mirrors etc...
• Severe – Vehicles that are almost condemned or with large distructions to the body.
• No- damage – No damage to the parts of the vehicle.

**Methodology**
1) Initially the existing training dataset was augmented and doubled the size. Then the
model fitting process was carried out to check the accuracy. 
2) As the next step after collecting more data, a new version of the first dataset was
created followed by a model fitting process with InceptionV3 and Resnet50.
3) Since it was identified that accuracy of the models trained with new dataset was higher,
an ensemble classifier was built using the best two models.

