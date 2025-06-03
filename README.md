# BMP Image with C++
This project consists in editing a BMP image to grayscale and displaying a piece of the image on a Nokia Display.

## Table of Contents
* General information
* Technologies used
* Usage
* Photos
* Contact

### General Information
- This project is based on a work for school
- The names of the variables and comments were written in portuguese

### Technologies Used
- Programming languages C and C++
- Microcontroller STM32 NUCLEO F446RE
- Nokia Display 5110

### Usage
The program has 3 user inputs and 2 outputs.

Inputs
1. The name of the BMP image
2. The threshold value for the image (from 0 to 255)
3. The bottom left x and y coordenates to display the image on the Nokia
     
Outputs
1. The grayscaled BMP image with the same name and _gs suffix 
2. A vector with the hex values for each 8 pixel of the cropped image to be used on the Nokia Display

Observations
1. The name of the image file has to be the same that was given by the user when executing the program
2. After given the name of the image file, there is a table with useful information of the bmp header
3. Download all files and include your bmp image and its name when executing `image_project.exe` as well

### Photos
- Ford Mustang Shelby gt500 (RGB extension)
<img src="https://github.com/vituzm/BMP_image./assets/134985122/48714152-004a-4a21-8c04-eca6c08364d2" alt = "Ford Mustang Shelby gt500 4k" width="50%" height="20%"/>

&nbsp; 
- Ford Mustang Shelby gt500 (GrayScale extension)
<img src="https://github.com/vituzm/BMP_image./assets/134985122/a979f95b-69ba-4bb2-8b9b-0edc73a86df2" alt = "Ford Mustang Shelby gt500 grayscale" width="50%" height="20%"/>

&nbsp;
- Ford Mustang Shelby gt500 (Mono extension | _*note: the threshold value is set to 90 here_)
<img src="https://github.com/vituzm/BMP_image./assets/134985122/8692683d-950c-44ff-b009-ce93d843e356" alt = "Ford Mustang Shelby gt500 mono" width="50%" height="20%"/>

&nbsp;
- Cropped image on a Nokia Display (_*note: the cropped image is the snake from the car model_)
<img src="https://github.com/vituzm/BMP_image./assets/134985122/ea4aa474-23cb-4204-b058-4570835bb942" alt = "Crop" width="50%" height="20%"/> 


## Contact
Created by [vituzm](https://github.com/vituzm) and [nicolaspessel](https://github.com/nicolaspessel) - feel free to contact us!
