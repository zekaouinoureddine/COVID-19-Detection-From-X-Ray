# COVID-19 Detection From X-ray Images Using Deep Learning 
Our project aims to create a solution that can easily detect covid-19 in an automated way, especially when The need for auxiliary diagnostic tools has increased as there are no accurate automated toolkits available. So, we're going to use Transfer Learning with advanced and popular architectures like VGG16, VGG19, ResNet50 and trying out SIAMESE with pre-trained weights on the popular ImageNet dataset. This implementation use Keras with a TensorFlow backend, and it will be performed Then adapted to our dataset which is full of X-ray images in Covid-19 and No_findings folders.

## Table of contents
- [Tech Stacks](#tech-stacks)
- [Data Set Description](#data-set-description)
- [Models Tested](#models-tested)
- [Results](#results)
- [Authors Infos](#authors-infos)
- [Conclusion](#conclusion) 
## Tech Stacks
* [x] Python
* [x] Keras/TensorFlow
## Data Set Description
Recent findings obtained using X-ray imaging techniques suggest that these images contain important information about the COVID-19 virus. The application of advanced artificial intelligence (AI) techniques coupled with X-ray imaging can be useful for the precise detection of this virus and can also help overcome the problem of the lack of specialist doctors in remote villages. Therefore, we will use a Dataset containing two classes, the first contains x-ray images of infected people and the second contains x-ray images of non-contaminated people as shown in the table below:
<table>
  <thead>
     <tr><th> COVID-19 </th> <th> NO-Findings </th></tr>
  </thead>
  <tr>
    <td>125 IMAGE</td>
    <td>500 IMAGE</td>
  </tr>
</table>
 
---
## Models Tested
 - [VGG16](./notebooks/Covid19Detection_VGG16.ipynb)
 - [VGG19](./notebooks/Covid19Detection_VGG19.ipynb)
 - [ResNet50](./notebooks/notebooks/Covid19Detection_ResNet50.ipynb)
 - [SAIMESE (Error ⁉️)](./notebooks/Covid19Detection_SIAMESE.ipynb)
 - [Our Own Architecture](./notebooks/Covid19Detection_Own_Architecture.ipynb): 

## Results
 - **Performance graphse:**

<p align="center">
    <img src="./assets/results.png" />
</p>


 - **Comparative table:** 

<p align="center">
    <img src="./assets/tableResults.PNG" />
</p>

### Conclusion
If you have taken a close look at the results section, we can say that:
- Accuracies graphs show that there is **no overfitting problem** which is great!
- Losses graphs show that our models are trained with a **good learning rate**, which is amazing!

So, we can see that our project is quite successful, and we have seen that from the height performances achieved.  However, there is still much more rooms for improvement, especially if we take into account the **quality** and the **size** of our dataset.

Finally, our best model is integrated into an Android application called [**COVID19KIT**](https://github.com/zekaouinoureddine/COVID19KIT) the mobile app created can detect COVID-19 from X-ray images in the phone gallery or even by taking a photo of your X-ray directly that you have  in your hands or on an electronic screen .

The screen below shows the **reserved app activities** for covid-19 detection:

![covid19kit.png](./assets/covid19kit.png) 
### Authors Infos
- LinkedIn: [Nour Eddine ZEKAOUI](https://www.linkedin.com/in/nour-eddine-zekaoui-ba43b1177/)
- Twitter: [@NZekaoui](https://twitter.com/NZekaoui)

---
 
[Back To The Top](#covid-19-detection-from-x-ray-images-using-deep-learning)
 
