# Binary-Classification-Model-Apples-Bananas-using-Julia-Flux

I did the "**Deep Learning with Flux**" course provided by **Julia Academy** (https://juliaacademy.com/courses/). I express my sincere gratitude to **Dr. Matt Bauman** for presenting this course and sharing the associated Jupyter Notebook. This notebook is associated with first lecture "**Introduction to Flux**" of the mentioned course.

As I was attending the first lecture, I realized I need to code myself to understand and record my inferences and in the process came up with this working notebook. Intent is to have this for my future reference as well as be useful to someone new to the field learning ML/DL.

This notebook provides a quick introduction to **Julia Flux** by having a **Binary Classification Model** implemented to **classify Apples and Bananas Images**. 

Details of what this notebook covers is listed below:
- How to setup the Environment
- Where to get the datasets from 
- Which packages to install and how
- Quick Introduction to Activation Function (Sigmoid)
- Quick Introduction to Loss and Optimizer Function
- Create a Model with Flux - Get output for a random input - Compare output with Manual Implementation
- Use Model As Is (without training) to classify Apples and Bananas
- Use Manually Trained Model to classify Apples and Bananas
- Use Flux Trained Model to classify Apples and Bananas
    - Visualization of the results using plots

We have **492 Apple** Instances and **490 Banana** Instances (Images) widely spaced apart per their **Red** and **Green** values. Refer below image:
<img src="images/Input.jpg">

By using the Flux Model, we are able to classify these instances into 2 Classes - **"0" for Apples** (1 to 492) and **"1" for Bananans** (493 to 982). Refer below image:

<img src="images/Prediction.jpg"> 
