# High-Frequency Electronic Circuits (HFEC) - 學習與研究筆記

## 📂 專案結構  
- CH1：高頻電子電路概論  
- CH2：傳輸線理論  
- CH3：阻抗匹配網路  

每個章節包含：  
- `HFEC_113_Lx.pdf` → 課堂講義  
- `Chx.pdf` → 自製筆記  

---

## **CH1：高頻電子電路概論**  
### 核心觀念  
- 電磁波頻段劃分（LF → EHF，30 kHz ~ 300 GHz）  
- 發射機與接收機基本架構（編碼器、調變器、天線等）  
- 訊號轉換流程：Baseband ↔ IF ↔ RF  

### 學習重點  
- 認識高頻電路的應用領域  
- 掌握各頻段特色與應用  
- 理解無線通訊系統的基本架構  

### 講義內容分析  
- **重要公式**  
  - 波長與頻率：![equation](https://latex.codecogs.com/svg.image?\lambda%20=%20\dfrac{c}{f}) 
  - 角頻率：![equation](https://latex.codecogs.com/svg.image?\omega%20=%202\pi%20f)  
- **應用案例**  
  - WiFi (2.4 / 5.8 GHz)、Bluetooth (2.4 GHz)、GPS (1.575 GHz)、5G (24–39 GHz)  

### 參考文獻  
- Pozar, *Microwave Engineering*, 4th ed., Wiley  
- Chang, *RF and Microwave Wireless Systems*, Wiley  

---

## **CH2：傳輸線理論 (Transmission Line Theory)**  
### 核心觀念  
- 高頻必須使用分佈參數模型  
- 傳輸線電壓/電流遵循波動方程  
- 阻抗不匹配導致反射與駐波  

### 學習重點  
- 低頻 vs 高頻電路的差異  
- 傳輸線方程與參數  
- 反射係數與駐波比的意義  
- Smith Chart 的設計應用  

### 講義內容分析  
- **重要公式**  
  - 波動方程式：  
    ![equation](https://latex.codecogs.com/svg.image?\frac{\partial^2%20V(z,t)}{\partial%20z^2}%20=%20LC%20\frac{\partial^2%20V(z,t)}{\partial%20t^2})  
  - 反射係數：![equation](https://latex.codecogs.com/svg.image?\Gamma%20=%20\dfrac{Z_L%20-%20Z_0}{Z_L%20+%20Z_0})  
  - 駐波比 (VSWR)：![equation](https://latex.codecogs.com/svg.image?\text{VSWR}%20=%20\dfrac{1%20+%20|\Gamma|}{1%20-%20|\Gamma|})  
- **應用情境**  
  - 天線輸入阻抗設計  
  - 微波電路測試與匹配  
  - 使用 Smith Chart 進行可視化分析  

### 參考文獻  
- Collin, *Foundations for Microwave Engineering*, Wiley  
- Saunders & Aragón-Zavala, *Antennas and Propagation*  

---

## **CH3：阻抗匹配網路 (Impedance Matching Networks)**  
### 核心觀念  
- 阻抗匹配目的：最大功率傳輸、消除反射  
- 常見方法：  
  - 四分之一波長變壓器  
  - L 型網路 (Lumped 元件)  
  - Stub 匹配 (單 Stub、雙 Stub)  
- 頻寬與實作性之間的取捨  

### 學習重點  
- 反射對功率的影響  
- 四分之一波長變壓器的限制  
- L-C 元件設計匹配方法  
- Stub 匹配技術  
- 寬頻匹配技巧  

### 講義內容分析  
- **重要公式**  
  - 最大功率傳輸條件：![equation](https://latex.codecogs.com/svg.image?Z_{in}%20=%20Z_{out}^*)  
  - 四分之一波長變壓器：  
    ![equation](https://latex.codecogs.com/svg.image?Z_{in}%20=%20\frac{Z_0^2}{Z_L},%20\quad%20l%20=%20\frac{\lambda}{4})  
- **應用情境**  
  - 天線阻抗調整  
  - 放大器輸入/輸出匹配  
  - 微波濾波器設計  

### 參考文獻  
- Pozar, *Microwave Engineering*  
- Matthaei et al., *Microwave Filters, Impedance-Matching Networks, and Coupling Structures*  

---
