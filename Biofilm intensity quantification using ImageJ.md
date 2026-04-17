# Biofilm intensity quantification using ImageJ
# Workflow

# Open image
File → Open → select your image (plate with different samples after crystal violet staining)

<img width="1200" height="582" alt="Plate example" src="https://github.com/user-attachments/assets/424f62c1-1139-4faa-b5de-8ebc29fbd6c5" />


# Convert to grayscale
Image → Type → 8-bit (converting it to grayscale for easy measurement)

# Invert the image
Edit → Invert

<img width="852" height="500" alt="image" src="https://github.com/user-attachments/assets/7c23fe09-42d0-46c4-9e60-101fc5d1c636" />



It will look like this:


<img width="1517" height="782" alt="image" src="https://github.com/user-attachments/assets/2698fcd2-724f-4fdc-a5b9-e09eb25106f9" />




# Set measurements
analyze → Set Measurements
You can check Area, mean gray value, integrated density etc

# Select a well (ROI) Regionof Interest
Use Oval tool:
Draw a circle inside one well
Avoid edges/reflections
Cntrl+T to add this in ROI manager


<img width="1517" height="923" alt="image" src="https://github.com/user-attachments/assets/aeb6fa5a-ce0e-4c40-9ce0-303e04c7a06f" />


Move the circle in each well and press Cntrl +T to add them in ROI manager

Now, select all ROI or the ROI that you want to measure
Than, press Cntrl+M


<img width="1526" height="927" alt="image" src="https://github.com/user-attachments/assets/942f1bc4-84a4-4673-93e6-e0b1aac8c4eb" />


# Calculation of intensity
If the ROI area is different between samples,
Integrated density = intensity × area

So, Intensity will be
Corrected Intensity=Average Sample Intensity − Average Background (control) intensity

