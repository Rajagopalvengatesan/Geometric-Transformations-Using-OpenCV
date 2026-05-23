# Geometric Transformations Using OpenCV

---

## Aim

To write a Python program using OpenCV to perform various geometric transformations on an image.

The program performs the following operations:

- Image Translation  
- Image Scaling (Resizing)  
- Image Shearing  
- Image Reflection (Flipping)  
- Image Rotation  

---

##  Software Used

- Anaconda – Python 3.7  
- Jupyter Notebook / VS Code  
- OpenCV (`cv2`)  
- NumPy  
- Matplotlib  

---

##  Algorithm

### Step 1:
Import the required libraries: OpenCV, NumPy, and Matplotlib.

### Step 2:
Read the input image in color mode.

### Step 3: Image Translation
- Create a translation matrix to shift the image  
- Move the image 50 pixels to the right and 80 pixels down  
- Apply transformation using `cv2.warpAffine()`  
- Display original and translated images  

### Step 4: Image Scaling
- Resize the image to 0.5× (downscale)  
- Resize the image to 2× (upscale)  
- Use `cv2.resize()`  
- Display original, downscaled, and upscaled images  

### Step 5: Image Shearing
- Create transformation matrices for:
  - Horizontal shearing  
  - Vertical shearing  
- Apply transformations using `cv2.warpAffine()`  
- Display original and sheared images  

### Step 6: Image Reflection
- Perform flipping using `cv2.flip()`:
  - Horizontal reflection  
  - Vertical reflection  
  - Both axes  
- Display all reflected images  

### Step 7: Image Rotation
- Create rotation matrices for:
  - 45° rotation  
  - 90° rotation  
- Use `cv2.getRotationMatrix2D()` and `cv2.warpAffine()`  
- Display original and rotated images  

---

##  Program

### Developed By:
**Name:** RAJA GOPAL V  

### Register No:
212223240134

---

##  Output

### Image Translation
- Original image is displayed   

<img width="680" height="412" alt="image" src="https://github.com/user-attachments/assets/a0978112-3e35-4bac-b3cd-284d78b25a1a" />



- Translated image (shifted right and down) is displayed 

<img width="648" height="466" alt="image-1" src="https://github.com/user-attachments/assets/aa41a017-cd61-4e4e-828a-084830b19032" />


### Image Scaling
- Original image is displayed  
- Downscaled image (0.5×) is displayed  
- Upscaled image (2×) is displayed  


<img width="701" height="256" alt="image-2" src="https://github.com/user-attachments/assets/cd1bfd03-d21d-4e61-a8cd-77063d88f2e1" />



### Image Shearing
- Original image is displayed  
- Horizontally sheared image is displayed  
- Vertically sheared image is displayed  

<img width="672" height="470" alt="image-3" src="https://github.com/user-attachments/assets/20688fb7-e832-4585-8fb2-7ee4c429d4ae" />


### Image Reflection
- Original image is displayed  
- Horizontally flipped image is displayed  
- Vertically flipped image is displayed  
- Both-axis flipped image is displayed  

<img width="1211" height="402" alt="image-4" src="https://github.com/user-attachments/assets/5b95ff74-e9aa-474c-af01-f1b8e887c856" />



### Image Rotation
- Original image is displayed  
- 45° rotated image is displayed  
- 90° rotated image is displayed  

<img width="466" height="285" alt="image" src="https://github.com/user-attachments/assets/37ef3c42-d5bd-48e6-aef5-acf0421feb8f" />


---

##  Result

Thus, various geometric transformations such as translation, scaling, shearing, reflection, and rotation are successfully performed using OpenCV. These transformations demonstrate how images can be spatially manipulated for different computer vision applications.
