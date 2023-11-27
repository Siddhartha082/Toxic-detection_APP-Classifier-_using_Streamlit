# Toxicity Detection-Classifier-App

![image](https://github.com/Siddhartha082/Toxic-detection_APP-Classifier-_using_Streamlit/assets/110781138/7627205d-86d6-499c-b39f-887629b91a65)

![image](https://github.com/Siddhartha082/Toxic-detection_APP-Classifier-_using_Streamlit/assets/110781138/b02dca35-592d-4da0-a294-3dc8a4533d4e)

![image](https://github.com/Siddhartha082/Toxic-detection_APP-Classifier-_using_Streamlit/assets/110781138/5396984e-a117-4028-a8f0-28961fc35378)

![image](https://github.com/Siddhartha082/Toxic-detection_APP-Classifier-_using_Streamlit/assets/110781138/2c067405-6e8f-4385-bd72-e37f63723c76)

![image](https://github.com/Siddhartha082/Toxic-detection_APP-Classifier-_using_Streamlit/assets/110781138/79183d5d-c3d7-4407-a02d-edf9103e598c)

https://www.section.io/engineering-education/building-a-toxicity-classifier/

Building a Toxicity Classifier using Python

This tutorial will use the detoxify pre-trained model to recognize toxic sentences. We will integrate this model into the Gradio app to build an interactive application that will allow the user to enter a sentence.

The model will give an output to indicate if the sentence is toxic or not.
Prerequisites

To follow along with this tutorial, you’ll need to:

•	Be familiar with machine learning modeling.

•	Use Google Colab or Jupyter Notebook.

•	Be familiar with the Jigsaw Multilingual Toxic Comment Classification dataset as the model has been trained on it.
Outline

•	The toxicity classifier

•	Installing the detoxify model and installing the necessary dependencies

•	Performing prediction using the model

•	Deploying the model as an application using Gradio
•	Wrapping up

The toxicity classifier

The toxicity classier can classify whether a particular text or sentence is toxic or not. Cyberbullying has been an issue ever since the rise of the social media era. Many people have experienced cyberbullying in one way or another.

On social media sites, there are a lot of comments that people make, and most of them have a significant amount of negativity and toxicity in them. Major technology companies have turned to machine learning to help with the automated classification of toxic content to combat toxic content and online abuse.
Indeed, many of these automated systems are deployed today. For example, this has been seen on Twitter, where the company has automatically flagged more than half of all tweets that violate its rules.

Just recently, in January 2021, Donald Trump’s Twitter account was permanently suspended as his account was deemed to cause incitement of violence. This automation was performed by a machine learning system.

An example of an open-sourced model built for this purpose is the toxicity classifier model built by Google’s research team. The model can detect whether sentences contain toxic content or not. This toxicity could be in the form of insults, threatening language, obscenities, identity-based hate, gender-based hate, or sexually explicit language.

This model is built on top of Google’s Universal Sentence Encoder model, which provides encoding over words and phrases and sentences, perhaps even longer pieces of texts. The model is trained on a collection of user-generated online news comments published between 2015 and 2017.

![image](https://github.com/Siddhartha082/Toxic-detection_APP-Classifier-_using_Streamlit/assets/110781138/b9e19c85-f69d-42fc-951a-21cd19c0a826)

![image](https://github.com/Siddhartha082/Toxic-detection_APP-Classifier-_using_Streamlit/assets/110781138/aa5d5ad1-b117-4acf-8268-94b7ac3894f4)

![image](https://github.com/Siddhartha082/Toxic-detection_APP-Classifier-_using_Streamlit/assets/110781138/8034a435-3d6b-445d-ad2d-62e289b1289f)

![image](https://github.com/Siddhartha082/Toxic-detection_APP-Classifier-_using_Streamlit/assets/110781138/ba592a99-6310-4ee9-9dc7-20c1abbee84c)


