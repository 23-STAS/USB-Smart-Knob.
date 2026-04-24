====================================================
  CUSTOM USB MEDIA CONTROL & VOLUME KNOB
====================================================

[INSERT PROJECT HERO IMAGE HERE]
(Example: final assembled device photo)

A DIY tactile desktop controller powered by the ESP32-S2, 
designed for creators who want fast, physical control over 
their workflow.

----------------------------------------------------
FEATURES
----------------------------------------------------

[INSERT FEATURE OVERVIEW IMAGE HERE]
(Example: labeled diagram showing knob, buttons, OLED)
<img width="803" height="633" alt="Screenshot 2026-02-12 220306" src="https://github.com/user-attachments/assets/ae41b46e-fe70-49cc-9fa9-33481dba05b5" />

[1] Rotary Volume Control
    - Smooth 360° rotation
    - Precise system volume adjustment

[2] Dedicated Shortcut Buttons
    - Undo (Ctrl + Z)
    - Redo (Ctrl + Y)
    - Vertical Scroll
    - Show Actions

[3] Creative App Integration
    - Adobe Suite compatible

[4] OLED Display Feedback
    - Shows status and active mode

----------------------------------------------------
HARDWARE REQUIREMENTS
----------------------------------------------------

[INSERT COMPONENTS IMAGE HERE]
(Example: all parts laid out)

Microcontroller : ESP32-S2 Mini → ₹270  
Rotary Encoder  : M274 Module → ₹50  
Display         : 0.91" OLED → ₹177  
Switches        : 5x Tact Switches → ₹30  
Misc            : Jumper Wires → ₹46  

----------------------------------------------------
DESIGN & ASSEMBLY
----------------------------------------------------
<img width="1302" height="842" alt="Screenshot 2026-02-11 233918" src="https://github.com/user-attachments/assets/c0f3a1b0-2a6a-4810-ac2f-c4b9372e7f79" />
<img width="1394" height="903" alt="Screenshot 2026-02-11 234305" src="https://github.com/user-attachments/assets/426e45ea-1b3d-4827-b027-9612d0277f47" />


[INSERT PCB / CIRCUIT DIAGRAM HERE]

Board Size :
    34.30 mm × 25.40 mm

Mount Points :
    - 20.40 mm
    - 2.50 mm

----------------------------------------------------

[INSERT WIRING DIAGRAM HERE]
(Show connections: ESP32 ↔ OLED ↔ Encoder ↔ Buttons)

Assembly Tips :
    - Center rotary encoder
    - Use I2C for OLED
    - Ensure stable mounting

----------------------------------------------------
SOFTWARE SETUP
----------------------------------------------------

[INSERT CODE SCREENSHOT HERE]
(Arduino IDE / PlatformIO)

Libraries :
    - Adafruit_SSD1306
    - USBHID
    - Encoder

----------------------------------------------------
KEY MAPPING
----------------------------------------------------

[INSERT UI / DISPLAY SCREEN IMAGE HERE]
(Optional: show OLED output)

Rotary → Volume  
Button 1 → Undo  
Button 2 → Redo  
Button 3 → Scroll  
Button 4 → Actions  

----------------------------------------------------
HOW IT WORKS
----------------------------------------------------

[INSERT WORKING DEMO IMAGE / SEQUENCE HERE]
(Example: knob in action, OLED updating)
<img width="687" height="582" alt="Screenshot 2026-02-12 215207" src="https://github.com/user-attachments/assets/7d1c3eb4-263a-4036-b73a-43737828d803" />




ESP32-S2 acts as a USB HID device:
    - Encoder → Volume control
    - Buttons → Shortcuts
    - OLED → Feedback

----------------------------------------------------
FINAL BUILD
----------------------------------------------------

[INSERT FINAL ENCLOSURE IMAGE HERE]
(3D printed case or finished product)

----------------------------------------------------
FUTURE IMPROVEMENTS
----------------------------------------------------

- Custom macros  
- Bluetooth support  
- RGB lighting  
- Software UI  

====================================================
