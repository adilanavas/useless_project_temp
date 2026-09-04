<img width="1280" height="640" alt="git (1)" src="https://github.com/user-attachments/assets/8920b256-2ba8-4988-b824-5351134eb4bd" />



# Pazham Meter 🎯


## Basic Details
### Team Name: Idly & Sambar


### Team Members
- Member 1: Adila Navas - LBSITW
- Member 3: Ahlam Anvarlal - LBSITW

### Project Description
Pazham Meter is a ridiculously serious attempt to answer one of life's most important questions: “How many pazhams long is this?”
Choose your favourite Pazham, point your phone at an object, and let Pazham Meter turn ordinary measurements into the only unit that truly matters — pazham.

### The Problem (that doesn't exist)
For centuries, humans have been forced to measure things in boring units like centimetres and metres. Some people even measure in feet!
But nobody has ever asked the more important question: “How many pazhams?”
We decided this unacceptable situation needed to change.

### The Solution (that nobody asked for)
Introducing Pazham Meter — a completely unnecessary but surprisingly useful banana-based measurement system. 
Pick a Kerala banana variety, measure an object, and Pazham Meter tells you exactly how many pazhams long it is. Because why use 100 centimetres when you could say 20 Njalipoovans?

## Technical Details
### Technologies/Components Used
For Software:
-  HTML5, CSS3, JavaScript 
-  Tailwind CSS, Google Fonts, Canvas 

### Implementation
For Software:
Pazham Meter is a frontend-only web application hosted on GitHub, so no additional package installation is required. The project can be run directly by opening the index.html file in a browser, or through a local development server for better camera support.

### Project Documentation
For Software:

# Screenshots (Add at least 3)
![Home Page](p1%20%281%29.jpeg)

![Measurement Screen](p1%20%283%29.jpeg)

![Result Screen](p1%20%284%29.jpeg)

![Monuments](p1%20%282%29.jpeg)

![Reference Selection](p1%20%285%29.jpeg)

![Fun Facts](p1%20%287%29.jpeg)

# Diagrams
+-----------------------------------------------------------------------+
|                            1. MEDIA INPUT                             |
|  • HTML5 Camera Stream (getUserMedia) OR Image File Upload            |
+-----------------------------------┬-----------------------------------+
                                    |
                                    v
+-----------------------------------------------------------------------+
|                       2. SCALE CALIBRATION                            |
|  • Auto-Detect ₹1 Coin (Radial Edge Detection)                        |
|  • OR Manual 2-Point Tap (Card / Paper / Custom Size)                 |
|                                                                       |
|  ➔ Derives Scale Ratio: pxPerCm = Pixel Length / Real Length (cm)     |
+-----------------------------------┬-----------------------------------+
                                    |
                                    v
+-----------------------------------------------------------------------+
|                      3. OBJECT MEASUREMENT                            |
|  • User taps Start & End points of target object                      |
|                                                                       |
|  ➔ Calculates Object Size: cm = Object Pixels / pxPerCm               |
+-----------------------------------┬-----------------------------------+
                                    |
                                    v
+-----------------------------------------------------------------------+
|                     4. BANANA UNIT MAPPING                            |
|  • Divides size (cm) by chosen variety unit size:                     |
|    - Njalipoovan  (10.0 cm)                                           |
|    - Palayamkodan (11.5 cm)                                           |
|    - Robusta      (18.5 cm)                                           |
|    - Nendran      (22.0 cm)                                           |
+-----------------------------------┬-----------------------------------+
                                    |
                                    v
+-----------------------------------------------------------------------+
|                        5. OUTPUT & EXPORT                             |
|  • Overlay measurement vector with repeating banana visuals          |
|  • Show total count in bottom results sheet                           |
|  • Generate downloadable annotated image canvas                       |
+-----------------------------------------------------------------------+

### Project Demo
# Video
[Add your demo video link here]
*Explain what the video demonstrates*

# Additional Demos
[Add any extra demo materials/links]

## Team Contributions
- [Name 1]: [Specific contributions]
- [Name 2]: [Specific contributions]
- [Name 3]: [Specific contributions]

---
Made with ❤️ at TinkerHub Useless Projects 

![Static Badge](https://img.shields.io/badge/TinkerHub-24?color=%23000000&link=https%3A%2F%2Fwww.tinkerhub.org%2F)
![Static Badge](https://img.shields.io/badge/UselessProjects--26-26?link=https%3A%2F%2Ftinkerhub.org%2Fevents%2F1M8ORET9A1%2Fuseless-projects-3.0)



