# Fluorescence quantification using ImageJ

# Workflow
# Open image
File → Open → select your image (GFP labelled photo)


<img width="776" height="875" alt="image" src="https://github.com/user-attachments/assets/e757c515-ee2f-4ad7-904d-40cd72096d98" />



# Split Channels
Image → Color → Split Channels (basically breaking with RGB color)
We will have 3 images



<img width="2137" height="977" alt="image" src="https://github.com/user-attachments/assets/942bf940-ccb6-4e1e-92c7-47aa521c9b7f" />


Since, its about GFP, select the green one!

# Convert to grayscale
Image → Type → 8-bit (converting it to grayscale for easy measurement)

# Set measurements
analyze → Set Measurements
You can check Area, mean gray value, integrated density etc

Now setting of ROI and measuring intensity is same as we did for biofilm intensity quantificatioin.
Remember to measure background or control signal, and probably adjust it.

Corrected IntDen=Raw IntDen−(Area×Background Mean)

Than, corrected Intensity can be statistically compared with other samples or control samples.
