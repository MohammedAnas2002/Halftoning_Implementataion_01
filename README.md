# Halftoning_Implementataion_01

---

## ✅ Implemented Methods 
### 1. Global Thresholding  
- Converts grayscale images to binary using a fixed threshold.  
- Simple but loses details in images with uneven lighting.
<img width="234" height="250" alt="image" src="https://github.com/user-attachments/assets/8d720a48-1e8d-4687-a92f-ead33d886ae8" />
<img width="250" height="250" alt="image" src="https://github.com/user-attachments/assets/28cca708-6d38-40d4-9a8b-9d04331b94c9" />

---

### 2. Ordered Dithering (Bayer 2×2, 4×4, 8×8)  
- Uses threshold matrices for dithering.  
- **2×2** → coarse, visible pattern.  
- **4×4** → smoother grayscale.  
- **8×8** → finer halftone.
<img width="230" height="250" alt="image" src="https://github.com/user-attachments/assets/30c624df-18fe-4067-bdec-67b589117deb" />
<img width="230" height="256" alt="image" src="https://github.com/user-attachments/assets/ba1c1276-cebc-425a-980c-37185d673318" />
<img width="238" height="253" alt="image" src="https://github.com/user-attachments/assets/a71e5c56-e45a-4c74-a565-7bb1b766ad78" />

---

### 3. Error Diffusion  
- Spreads quantization error to neighboring pixels.  
- Implemented algorithms:  
  - **Floyd–Steinberg** (simple, high quality).  
  - **Jarvis, Judice & Ninke (JJN)** (smooth, 12 neighbors).  
  - **Stucki** (sharp, different weights).  
<img width="229" height="248" alt="image" src="https://github.com/user-attachments/assets/8820d228-c911-4166-83de-d085ff6d5ee9" />
<img width="250" height="248" alt="image" src="https://github.com/user-attachments/assets/b2d411ba-fefb-40c8-8cef-04598faaeee0" />
<img width="213" height="235" alt="image" src="https://github.com/user-attachments/assets/5b381540-5fbf-4df7-8bfe-1a1fdc6608ce" />

---

### 4. Random & Blue-Noise Dithering  
- **Random dithering** → breaks patterns with noise.  
- **Blue-noise dithering** → high-frequency noise for fewer artifacts.
<img width="224" height="249" alt="image" src="https://github.com/user-attachments/assets/14cdd4ab-362d-4c81-89d6-5e0e5ffea533" />
<img width="233" height="249" alt="image" src="https://github.com/user-attachments/assets/5b6bdca0-ce10-458e-8d84-72b8e50ff66b" />

---

### 5. CMYK Halftone Preview  
- Simulates the **printing process** using CMYK channels.  
- Each channel halftoned separately and combined to preview print appearance.
<img width="363" height="386" alt="image" src="https://github.com/user-attachments/assets/808564ed-9ffe-4af1-962b-89f7c1c52eb5" />

---



