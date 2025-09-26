# DIY 3D-Printed BLDC Motor

Scroll down for the demo videos

### 1. 3D-Printed Parts  
<img src="https://github.com/user-attachments/assets/6aaf33a3-73a0-4dd1-91ba-5e552e39bd1f" width="400">

---

### 2. Winding the Stator  
After winding the 3 phases with insulated copper wire:  
<img src="https://github.com/user-attachments/assets/6ff5c589-9ef0-4acd-8447-f76fcb8dbe27" width="400">

---

### 3. Controller Setup  
Three half-bridges (two MOSFETs + two switches each) control the current through the motor phases:  
<img src="https://github.com/user-attachments/assets/46c14680-b4f9-4bac-8be6-177d3579f620" width="400">

---

### 4. Manual 6-Step Commutation  
Manually switching the BLDC with a 6-step sequence:  
A+ B- >> A+ C- >> B+ C- >> B+ A- >> C+ A- >> C+ B-

The third phase is always floating.  

**Demonstration video:**  
<video src="https://github.com/user-attachments/assets/8ec74159-b880-4181-af10-d34e4422a3e5" width="400" controls></video>

---

### 5. Automated Switching  
After manual testing, control is handed over to a microcontroller to handle commutation at higher speed.  

**Video demo:**  
<video src="https://github.com/user-attachments/assets/efec8cac-a067-41b0-9e34-fba383cbe5c5" width="400" controls></video>
