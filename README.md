# **Color Recognition Application**

This repository contains a **Color Recognition Application** that allows users to recognize colors from an image. The application supports color blindness simulations (Protanopia, Deuteranopia, and Tritanopia) and displays detailed color information (RGB, HEX, and color name). The project is implemented in Python using **OpenCV**, **NumPy**, and other libraries.

---

## **Table of Contents**
- [Overview](#overview)
- [Features](#features)
- [Files and Folders](#files-and-folders)
- [Requirements](#requirements)
- [Usage Instructions](#usage-instructions)
- [Key Functionalities](#key-functionalities)
- [Simulation Modes](#simulation-modes)
- [How to Contribute](#how-to-contribute)
- [License](#license)
- [Acknowledgements](#acknowledgements)

---

## **Overview**

The **Color Recognition Application** identifies colors from images, simulates various color blindness types, and allows users to copy color information to the clipboard. It provides an interactive interface where users can double-click on a color in an image to get its name, RGB, and HEX values.

The application also includes a help text feature to guide users through its functionalities.

---

## **Features**
- Recognize and display color information (RGB, HEX, and color name).
- Simulate color blindness types:
  - **Protanopia**
  - **Deuteranopia**
  - **Tritanopia**
- Copy color details to the clipboard with a single key press.
- Resize images to fit a fixed application window.
- Interactive user interface with mouse and keyboard controls.
- Helpful on-screen text to guide users.

---

## **Files and Folders**
The repository contains the following files and folders:

### **Files**
- `recog2.py`: The main Python script for the application.
- `colors.csv`: A CSV file containing the color dataset used for recognition.
- `colors.html`: An HTML file (optional, for displaying colors in a browser).

### **Folders**
- `img/`: Folder containing sample images to test the application.
- `output/`: Folder to save processed images or outputs, if applicable.

---

## **Requirements**

To run the project, ensure you have the following dependencies installed:

```bash
pip install numpy pandas opencv-python pyperclip tkinter
```
---

## **Usage Instructions**
### **1. Clone the Repository**
Clone the repository to your local machine:

```bash
git clone https://github.com/Zero-Asif/RGB_classification_-_colorblind_detection.git

```

### **2. Run the Application**
Execute the script using Python:

```bash
python recog2.py
```

### **3. Select an Image**
When prompted, select an image file (e.g., .jpg, .png) using the file dialog.

### **4. Interact with the Application**
Double-click on the image to get color information.
Use keyboard shortcuts to switch between simulation modes.

## **Key Functionalities**

### **Mouse Interactions**
- **Double-click** on any point in the image to display:
  - **Color Name**
  - **RGB Values**
  - **HEX Value**

### **Keyboard Shortcuts**
- **`n`**: Switch to normal vision mode.
- **`p`**: Switch to protanopia simulation.
- **`d`**: Switch to deuteranopia simulation.
- **`t`**: Switch to tritanopia simulation.
- **`c`**: Copy the current color information to the clipboard.
- **`ESC`**: Exit the application.

---

## **Simulation Modes**

The application supports the following color blindness simulations:

1. **Normal Vision (Default)**: No simulation applied.
2. **Protanopia**: Red-green color blindness affecting red cones.
3. **Deuteranopia**: Red-green color blindness affecting green cones.
4. **Tritanopia**: Blue-yellow color blindness affecting blue cones.

Each simulation modifies the displayed image to represent how colors are perceived under these conditions.
---
## **How to Contribute**
Contributions are welcome! Follow these steps:

1. Fork this repository.
2. Create a new branch:
 ```bash
 git checkout -b feature-name
 ```

3. Commit your changes:
   ```bash
   git commit -m "Add new feature"
   ```

4. Push to your branch:
```bash
   git push origin feature-name
   ```
5. Open a pull request.

---

## **License**

This project is licensed under the **MIT License**. See the [LICENSE](LICENSE) file for more details.

---

## **Acknowledgements**

- [OpenCV Documentation](https://docs.opencv.org/)
- [NumPy Documentation](https://numpy.org/doc/)
- [UCI Machine Learning Repository](https://archive.ics.uci.edu/)
- [Tkinter Documentation](https://docs.python.org/3/library/tkinter.html)

---

## **Author**

- **Asifuzzaman**  
- GitHub: [Zero-Asif](https://github.com/Zero-Asif)
