Qualcomm VisionX 

PROBLEM STATEMENT: 
Challenge 1: Removing Reflections from Images

Deep Learning for Reflection-less Images


---

### **Datasets**  
#### **For Training**:
- **Synthetic Images**: 7,643 samples derived from the Pascal VOC dataset, using the same synthesis protocol as ERRNet.  
- **Real Images**: 90 real-world images from the Berkeley Real Dataset.  

#### **For Testing**:
- **Real20**: A set of 20 real-world images from the Berkeley Real Dataset.  
- **Real45**: A set of 45 images from the CEILNet dataset.  
- **SIR Dataset**: Includes three subsets (Solid, Postcard, Wild). Due to restrictions, this dataset is not included. You’ll need to download it and arrange it as specified in the code.

---

### **Results**  
#### **Before**:

![image](https://github.com/user-attachments/assets/cbbda58b-7e08-49e6-8880-5f2238e6abd6)![image](https://github.com/user-attachments/assets/81d72dbe-9f7a-490c-827d-b7539d787e2c)

#### **After**:

![image](https://github.com/user-attachments/assets/1e98bbad-c91f-485e-84e0-d476343a922b)![image](https://github.com/user-attachments/assets/fb5c034b-7b28-4034-ab67-df8f3517c297)

---
### **Conclusion**  
This approach offers an effective two-stage solution for single-image reflection removal, using reflection estimation to guide transmission recovery through its innovative Reflection-Aware Guidance module. Tested on multiple datasets, RAGNet achieves good results, producing clear, reflection-less images with PSNR and SSIM metrics. Its robust design and strong performance make it a valuable contribution to image processing, with significant potential for real-world applications.

