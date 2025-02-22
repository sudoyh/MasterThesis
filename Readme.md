# Face Recognition for Masked Individual face

<img src="yhimages/1.png"  alt="image" style="width: 600px; height: 400px;">



---
---
<br>

# Feature

1. Face Authentication with Mask Support:<br>    
<p>
Developed a face recognition system that enables identity verification even while wearing a mask, addressing the issue where iPhone Face ID fails with masked faces at 2021.
</p>
<br>
<br>

2. Image Preprocessing & Normalization:<br>   
<p>
Applied pixel normalization and preprocessing techniques to enhance recognition accuracy.
</p>
<br>
<br>

3. One-Shot Learning Implementation:<br>   
<p>
Used one-shot learning to improve model efficiency and performance with limited training data.
</p>
<br>
<br>

4. Positive & Negative Pair Formation:<br>    
<p>
Created positive and negative face pairs to optimize the training process for better identity verification.
</p>
<br>
<br>

5. Recognition with Disguises:<br>   
<p>
Enabled face authentication even when wearing hats, glasses, wigs, or other disguises.
</p>
<br>
<br>



---
---
<br>

# Core technologies

- **PyTorch & Keras** - Deep learning frameworks used for building and training the face authentication model. PyTorch provides flexibility in model development, while Keras simplifies experimentation.<br>

- **MobileNet** - A lightweight and efficient convolutional neural network (CNN) optimized for mobile and embedded vision applications, ensuring fast face recognition with minimal computational cost.<br>

- **Siamese Network** - A neural network architecture that learns to distinguish between pairs of images by computing similarity scores, making it ideal for one-shot learning in face authentication.<br>

- **Metric Learning** - A technique that focuses on learning an embedding space where similar images (faces) are placed closer together while different images are pushed apart, improving recognition accuracy.<br>

---
---
<br>

## 1. Dataset

<table>
  <tr>
    <td><img src="yhimages/2.png" width="250"></td>
    <td>
      •63 faces were extracted.<br>
      •The gender consisted of 21 females and 42males.<br>
      •The training dataset used image with faces covered by various disguise.<br>
      •It consisted of a total of 7,560 images, with approximately 15 images per one person.<br>
      •The test dataset used images with faces covered by masks.<br>
      •It consisted of a total of 315 images, with approximately 5 images per person.<br>
    </td>
  </tr>
</table>


<br>


---
---
<br>

## 2. Development purpose


- **Face recognition of users wearing masks in limited dataset**  
=> Few shot learnig, Metric learning<br>
<br>

- **Lightweight network applicable to embedded devices**  
=> Modified MobileNet V3<br>
<br>


- **Verification of network accuracy and stability according to changes in optimization function** 
=> Best choice in first-order function optimizer<br>
<br>


---
---
<br>



## 3. Works


<img src="yhimages/3.png" width="600">

#### **Simames Network Network + MobileNet V3 + Contrastive Loss** 


<br>

---
---
<br>





## 4. Results


<table>
  <tr>
    <td><img src="yhimages/1.png" width="250"></td>
    <td>
      •Accuracy is 96.56%<br>
      •A dissimilarity of 0.5 or less indicates that the faces are the same.<br>
      •A dissimilarity of more than 0.5 indicates that the faces are different.<br>
    </td>
  </tr>
</table>





<br>

---
---
<br>





# Paper download


[📄 Download Paper](https://github.com/yh/MasterThesis/yhimages/sample.pdf)

---
---
<br>
