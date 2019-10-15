# RUSH-Vesicle-Analysis
A FIJI / ImageJ macro to measure number of cytoplasmic vesicles in Z-stack microscopy images

# Goal
The macro faciliates the quantification of cytoplasmic vesicles in single or Z-stack microscopy images. This macro was designed for retention using selective hooks (RUSH) constructs (Boncompain et al. 2012). It will also work for any other construct or probe that label vesicular structures.

# Installation
Simply copy the macro file to your macro folder in your [Fiji](https://imagej.net/Fiji) directory and restart Fiji. You can access the macro from the Plugin section in Fiji.

# Usage
Acquire single stack or Z-stacks images to cover the full volume of cells that express your reporter or are labeled with the probe of your interest.

Start the macro and choose as many cells you want to analyze. Select your cell(s) by e.g. polygon or rectangular selection tools. Next, select a suitable threshold and press apply to extract the vesicular objects in a binary image. The macro uses the particle analyzer of the selected cell(s) and prints the number of selected vesicles to the log file. All processed images and log files will be saved in a results folder in the image directory.

# Citation
If you used the RUSH-Vesicle-Analysis macro or modified it, please cite our work.

Deng, Y., Pakdel, M., Blank, B., Sundberg, E.L., Burd, C.G., von Blume, J., 2018. Activity of the SPCA1 Calcium Pump Couples Sphingomyelin Synthesis to Sorting of Secretory Proteins in the Trans-Golgi Network. Dev. Cell 47, 464-478.e8. 
https://doi.org/10.1016/j.devcel.2018.10.012
