# ByzArt Dataset - (Under Review in ACM JOOCH)

![License](https://img.shields.io/badge/license-MIT-blue.svg)
![GitHub issues](https://img.shields.io/github/issues/p1nkpan7er/ByzArt2K)
![GitHub stars](https://img.shields.io/github/stars/p1nkpan7er/ByzArt2K)

This dataset was manually constucted and annotated using images of icons found in photographs of Mount Athos, Greece and the exhibition of the Byzantine Museum in Athes, Greece. 


---

## 📖 About The Project
Byzart aims to be used for object detection of Orthodox Christian art, which currently is underrepresented in the field of AI.
* The main motivation of this project is to facilitate a new avenue of AI research in the domain of art and in particular Christian art.
Provide a more detailed explanation of your project.
* Our dataset has been used for both complex and more lightweight networks: ranging from YOLO8 to YOLO12 networks, as well as DETR/RT-DETR and RF-DETR.
* If you would like to test and replicate my work, you can download the models from Roboflow and train them on Byzart using your own GPU, or even better train them on Google Colab!
* We believe that the ByzArt dataset contributes to a currently underrepresented avenue of religious art data for deep learning technologies.

---

## 📊 Dataset Preview

Here are some sample images from the datasets, which are located in the `/ByzArt2K/Documents/ByzArt` directory of this repository.

### Image Samples


| Sample 1 / Sample 2 | Sample 3 / Sample 4 |
| :---: | :---: |
| ![Alt text for image 1](./Documents/ByzArt/byzart_base.v1i.voc/test/138876558_jpg.rf.ce3e810e83dab7aec9b72f6c1cebaa7c.jpg) | ![Alt text for image 2](./Documents/ByzArt/byzart_base.v1i.voc/test/167880916_jpg.rf.eeb9c8b686d384bbfa0e97557a671425.jpg) |
| *Caption: An icon depicting one of the holy church fathers* | *Caption: An icon depicting the scene of the nursing mother* |
| ![Alt text for image 3](./Documents/ByzArt/byzart_base.v1i.voc/valid/00004741-2_jpg.rf.b962ab350648499b555eca807ff4f4c7.jpg) | ![Alt text for image 4](./Documents/ByzArt/byzart_base.v1i.voc/valid/474031874_jpg.rf.76387b67a83fe9597e5544e14e653ae8.jpg) |
| *Caption: Holy men gathering* | *Caption: Saint Catherine* |



---

## 📁 Dataset Structure

The dataset is presented here in PASCAL VOC annotation format in order to facilitate an easier inspection of the bounding box annotations in the corresponding .xml files of each image.
The datasets have been split originally in a 70-20-10 split fashion. Since its best practice to only perform image augmentation on the training splits, the 3x and 5x dataset versions have an increased train, however the other splits remain same as in base
