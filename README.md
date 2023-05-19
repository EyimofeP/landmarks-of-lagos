# The Landmarks of Lagos

[Check it Out!](https://eyes-of-landmarks.streamlit.app/)
___
The aim of this project is to build an application that can classify seven (7) popular architectural landmarks that can be found in Lagos state, Nigeria. These landmarks include

* Aro Meta Statue

    *   <img src="data/aro meta statue/lagosthreewisemenstatue0.jpeg" alt="aro meta" style="height: 300px; width:500px;"/> 

<br />

* Cathedral Church of Christ, Marina

    *   <img src="data/cathedral church marina/cathedralchurchmarina56.jpeg" alt="cathedral church of christ" style="height: 300px; width:500px;"/> 

<br />

* Civic Center & Towers Lagos

    *   <img src="data/civic center lagos/civiccenterlagos13.jpeg" alt="Civic Centre" style="height: 300px; width:500px;"/> 


<br />

* Lekki-Ikoyi Link Bridge

    *   <img src="data/lekki ikoyi bridge/lekkiikoyibridge0.png" alt="link bridge" style="height: 300px; width:500px;"/> 

<br />

* National theatre lagos

    *   <img src="data/national theatre lagos/nationaltheatrelagos1.jpeg" alt="national theatre" style="height: 300px; width:500px;"/> 

<br />

* Necom house lagos

    *   <img src="data/necom house lagos/necomhouselagos6.jpeg" alt="necom" style="height: 300px; width:500px;"/> 

<br />

* Tafawa Balewa Square (TBS)

    *   <img src="data/tafawa balewa square/necombuildinglagos75.jpeg" alt="tbs" style="height: 300px; width:500px;"/> 

___
The data was scraped using the [Google Image Scraper](https://github.com/ohyicong/Google-Image-Scraper) tool to extract all the images from Google

___

* Extracted the data 

* Arranged and label the data

* Performed various Data Preprocessing techniques such as converting images into tensors and feature normalization/scaling

* Convolutional Neural Networks (CNN) using Data Augmentation and Transfer Learning / Pretrained Model to achieved best performance

* **Tuned Inception V3** achieved best performance with **99% training accuracy** and **97.2% test accuracy**

<!-- * Model was deployed on a web application built using **Django** available at [Dementia Predictor](https://dementia-predictor.herokuapp.com/) -->
___
## Model Performamce
Accuracy with Confusion Matrix was used to evaluate performance. 

* **Tuned Inception V3 with Data Augmentation**
    * Training Accuracy : 99%
    * Testing Accuracy : 97.2%
    * Confusion Matrix
    ![CF of base](plots/cf.png)
___
## Model Deployment
The final model with the best score was deployed on a web application built with **Streamlit**

![Web application of the model](plots/app.png)
___ 
