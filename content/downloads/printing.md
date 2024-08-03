+++
title = 'How to Download and Print 3D Text Objects'
omit_header_text = true
featured_image = ""
layout = "single"
+++

## Overview

This document serves as an instructional write-up explaining how to download and 3D print text objects. The only software needed is a 3D printer slicing application. This instructional will be specifically for the free software, Ultimaker Cura, version 3.4.1. Note, other versions of Cura or other slicing software packages may not share the exact same user interface, but the general steps for 3D printing a digital file should be applicable.

## Downloading STL Files

First select the object you would like to download. You can also use the preview window to view the different 3D models. Select the download button to begin downloading the object in the form of a .STL file type.

## Preparing to 3D Print

Once the .STL file has been downloaded, open up Cura. The general layout of the application can be seen below.

If this is your first time using Cura, you will have to configure your 3D printer settings so that the software understands the parameters of your machine. All settings can be found in Preferences à Configure Cura.

From here, select *Printers: Add*. At this point, you should add the model of 3D printer that most closely resembles the model you will be using. Select “Other” if your model is not listed. After establishing your model 3D printer, select *Machine Settings*. Enter all the settings for your specific printer. The key information to verify under the “Printer” tab are the X, Y, and Z dimensions of your print volume under “Printer Settings” (shown below). This is the maximum printing volume your machine is capable of, which can be found on the manufacturer’s website or found in manuals. The other critical settings to verify are the “Nozzle size” and “compatible material diameter” under the “Extruder I” tab. The most common nozzle size is 0.4 mm and the most common plastic filament diameter is 1.75 mm, but the dimensions of your hardware and material may vary.

Now that Cura is all set up, you can either drag and drop your .STL file directly into Cura or select *File: Open File(s)*. The model should now appear on the virtual build plate within Cura. If you left click the 3D model, you can then manipulate it using the various vertically stacked icons on the left side of the application, including *Move*, *Scale*, *Rotate*, etc. On the right side is the Print Setup where you can modify the actual print settings.

For the 3-D text objects, a default profile of “Draft Quality” can be used. The key settings to note are the 0.2 mm layer height and 20% infill. The infill can be reduced to 15%, however, to reduce print time and material. Additionally, no support material needs to be generated, and the only build plate adhesion type necessary is a skirt. For higher resolution 3D prints, a default profile of “Fine” can be used, which primarily reduces the layer height to 0.1 mm. This will produce higher quality prints but will also double the amount of material used and greatly increase print time.

Note that the 3-D text object files for *Touch This Page!* have already been scaled 150% from their original 3D scans. Characters have also been extruded to improve tactile legibility. To print the objects to their original dimensions, apply a uniform scaling factor of 66.67% using the scaling icon on the left side. We have found that printing them with a vertical orientation (rather than flat on the bed) can also improve their tactility.

­Once all desired settings have been applied, click “Prepare,” and Cura will slice the 3D model into layers, and create a G-code file to be read by the 3D printer. Once the file is done slicing, save the G-code file to a USB or other storage device that can be connected to your 3D printer. Simply connect your storage device to your 3D printer, select the file, and begin printing!