# Halftoning_Implementataion_01
# 🖼️ Digital Halftoning Methods  

This project implements and visualizes different **halftoning techniques** for grayscale and color images.  
Halftoning simulates continuous-tone images using binary patterns (black and white dots), which is widely used in printing, display rendering, and image compression.

---

## ✅ Implemented Methods 
### 1. Global Thresholding  
- Converts grayscale images to binary using a fixed threshold.  
- Simple but loses details in images with uneven lighting.

---

### 2. Ordered Dithering (Bayer 2×2, 4×4, 8×8)  
- Uses threshold matrices for dithering.  
- **2×2** → coarse, visible pattern.  
- **4×4** → smoother grayscale.  
- **8×8** → finer halftone.

---

### 3. Error Diffusion  
- Spreads quantization error to neighboring pixels.  
- Implemented algorithms:  
  - **Floyd–Steinberg** (simple, high quality).  
  - **Jarvis, Judice & Ninke (JJN)** (smooth, 12 neighbors).  
  - **Stucki** (sharp, different weights).  

---

### 4. Random & Blue-Noise Dithering  
- **Random dithering** → breaks patterns with noise.  
- **Blue-noise dithering** → high-frequency noise for fewer artifacts.  

---

### 5. CMYK Halftone Preview  
- Simulates the **printing process** using CMYK channels.  
- Each channel halftoned separately and combined to preview print appearance.  

---



