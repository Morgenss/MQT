# MicrostructureQuantificationTool - MQT

<p align="center">
    <img width= "60%"; src="https://github.com/Morgenss/MQT/assets/86916321/56b3a15e-ca2a-4700-9578-e42bf85b9d82">
</p>

This tool is designed to quantify properties of particle in matrix microstructures. It combines <strong>automatic detection algorithms</strong> with <strong>convenient </strong><strong>ways of manual editing</strong> to provide fast and accurate image characterizations. 
Each button, slider and field visible in the app can be hovered over with the mouse to get brief description of their function. For more detailed information, you can consult the different tabs of the Help page in the application itself.

The following infographic depicts an exemplary workflow and quantifyable properties of an image with this tool:

<p align="center">
    <img src="https://github.com/Morgenss/MQT/assets/86916321/4365a3a7-a718-4496-8d62-5edde27b2a07">
</p>



## Motivation and Goal
This tool was developed during my PhD-thesis to treat low-contrast images of phase separation microstructures in glass. The primary challenge with such images is that common thresholding or detection algorithms struggle to interpret the entire microstructure, even when the preprocessing steps and parameters of the detection algorithms are carefully chosen. Since the machine interpretation cannot grasp all the nuanced features of low-contrast microstructures, manual adjustments based on human judgment and experience are still necessary for accurate quantification.

Thus, this tool aims not to introduce new or advanced algorithms compared to existing software but to combine an easy-to-understand user interface with simple and fast detection algorithms that can be conveniently supplemented with direct manual edits based on human judgment. Consequently, providing a faster way to extract information from low-contrast images. Furthermore, the tool allows the calculation of various microstructural features, and the results can be easily exported as images or to the clipboard for use in Excel or similar software.


## Installation Instructions

There are two different installation methods available by using the corresponding file:
- <strong> MicrostructureQuantificationTool.mlappinstall </strong> to integrate the tool into MATLAB, it will then be available under the apps tab in MATLAB. Requires an active MATLAB installation and license with the image processing toolbox
- <strong> MQTInstaller_web </strong> is the standalone version and can be used without an active MATLAB installation or license. Its an executable file that will download roughly 2GB of libraries to install the tool. Afterwards, it can be used as a standalone application.
