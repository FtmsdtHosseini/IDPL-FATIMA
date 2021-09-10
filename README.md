# IDPL-LSPOD
This repository contains IDPL-LSPOD that is Large-Scale Persian OCR Dataset for Persian optical character recognition researches.

A demo of the dataset is provided in "Demo of IDPL-LSPOD.zip" which contains 90 Images.

The full dataset is uploaded in google drive and you can download it here.

To use the complete dataset, you must submit your request to one of the following communication channels:
 + ftmsdt_hosseini@yahoo.com 
 + https://www.linkedin.com/in/fatemesadat-hosseini/and 

we will provide you with the password needed to extract IDPL-LSPOD.zip.

**Notes:**
+ *IDPL is abbreviation of “Intelligent Data Processing Laboratory”.*

+ *LSPOD is abbreviation of “ Large-Scale Persian OCR Dataset”.*

## IDPL-LSPOD Description
IDPL-LSPOD:
+ Is an Artificial image dataset of printed Persian text.

+ Has 30,138 images in tif format, each image containing a line of real Persian text.

+ The dimensions of the images are 700 x 50 pixels.

+ 50% of the images are generated with a white background, 40% with a noisy background and 10% with a textured background.
 
+ To increase the similarity of images with real images, we have added distortion and blur to 10% of the total images.
  + 4% sloping distortion.
  
  + 1% sine wave distortion.
 
  + 3% blur.
  
  + 2% both blur and one type of distortion.
  
+ To generate images, 11 common Persian fonts with 2 font styles and 7 font sizes have been used.

+ To record image information, we have created a file that has 7 columns and 30,138 rows, each row corresponding to an image.
 
**Notes:**

+ *we generated IDPL-LSPOD's images by using the Python programming language.*

+ *we used MirasText Dataset to generate text of each image*
## Summery of IDPL-LSPOD
|#######| **Plain white** | **Noisy** | **Texture** | **Total image**| **Total Lines** | **Total Words** |
:-:|:-:|:-:|:-:|:-:|:-:|:-:
| **Each font** | 1,370 | 1,096 | 273 or 274 | 2739 or 2740 | 2739 or 2740 | 41,085 or 41,100 |
| **Total fonts** | 15,070 | 12,056 | 3,012 | 30,138 | 30,138 | 452,070 |

## Some of generated images in png format
#### *Plain white background:*
![](images/16475.png)
#### *Noisy background:*
![](images/08252.png)
#### *Texture background:*
![](images/08230.png)
#### *Texture background, Sinwave distortion:*
![](images/05044.png)
#### *Noisy background, Sloping(-1 degree) distortion:*
![](images/21991.png)
#### *Plain white background, Sinwave distortion, Gaussian blur:*
![](images/14770.png)
