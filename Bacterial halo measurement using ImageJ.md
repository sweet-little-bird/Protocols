# Download and Install ImageJ
Go the official site:
```
https://imagej.net/ij/
```
Go to Download tab and select the software installer according to your device type.
You can un-archive the software into a folder. You can run the software without installing it.

# Workflow
# Open image
File → Open → select your image (bacterial plate with a halo created by another bacteria in center, or anything)
# Convert to grayscale
Image → Type → 8-bit (converting it to grayscale for easy measurement)
# Adjust the threshold
Image → Adjust → Threshold
# Analyze area or intensity or diameter
analyze → Set Measurements
You can check Area, mean gray value, integrated density, diameter etc
Than, Analyze → Measure
# To measure halo (diameter or area)
File → Open → select your image


<img width="422" height="447" alt="image" src="https://github.com/user-attachments/assets/4179d6d8-fd91-4ede-b9b9-6195b7438022" />


#Set scale
analyze → Set scale (for example, if the plate is 90mm, set it as 90mm)
First, draw a line across the plate 

<img width="1305" height="642" alt="image" src="https://github.com/user-attachments/assets/2e8670ae-7664-418b-8338-c8b496391420" />





#Draw outer circle (halo edge)
use oval tool, fit it to the outer halo boundary, Cntrl+M to measure
