# Bldc motor and controller from scrach

Start with print som 3d printd motor parts like this:
![3d-printed-parts](https://github.com/user-attachments/assets/6aaf33a3-73a0-4dd1-91ba-5e552e39bd1f)

After winding 3 phases with insulated copper wire:
![after_winding](https://github.com/user-attachments/assets/6ff5c589-9ef0-4acd-8447-f76fcb8dbe27)

Setting up some controller, 3 half bridges (2 mosfet and 2 switched for each) to control the flow though the phases: 
![controller](https://github.com/user-attachments/assets/46c14680-b4f9-4bac-8be6-177d3579f620)

When every thing is setup, starting with manually switching a 6-step sequence to get the motor running
1. A+  B-
2. A+  C-
3. B+  C-
4. B+  A-
5. C+  A-
6. C+  B-
and the third phase should always be floating.
Here is a little demonstration:

https://github.com/user-attachments/assets/8ec74159-b880-4181-af10-d34e4422a3e5

After that, need some help of my little friend that can switch a bit faster than me:

https://github.com/user-attachments/assets/efec8cac-a067-41b0-9e34-fba383cbe5c5
