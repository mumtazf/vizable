# Vizable
Image-to-Audio Assistant for Visual Disabilities

### What is Vizable? 
Vizable is an app developed for individuals with visual disabilities. The app is primarily focused on converting visual input (in the form of images) to audio in real-time so that the user is able to identify the object in front of them. 

It was made with the purpose of catering to a usually underserved demographic. The image-to-speech technology is made more accessible by incorporating a real-time translation tool that assists the user in receiving translated audio output. 

### What technologies did we use? 
We primarily used [CLIP model (Contrastive Language-Image Pre-training)](https://openai.com/research/clip) developed by OpenAI. We tested this model on the [Vizwiz dataset](https://vizwiz.cs.colorado.edu/VizWiz_visualization/view_dataset.php) for our usecase. The Vizwiz dataset comprises of images that are clicked by individuals with visual impairements so we thought it would be a useful dataset to test the model against.

We conducted accuracy score evaluations of how CLIP peformed on the Vizwiz dataset. After reaching a satisfactory threshold of accuracy, we decided to test the model on images captured by our own phones. 

On successfully completing these two parts, our team created a fullstack mobile application using React Native. We incorporated the CLIP model into our backend and we designed our front-end so that our users can click images and have real-time audio narration of the image they captured. 

### Demo Video: 


https://user-images.githubusercontent.com/88557841/221958889-eb5e035b-26ff-4efa-bf2a-23c2515b4f8d.mp4



Credits: 
This project was completed with the guidance of project advisor SouYoung 
This project was done in collaboration with Aracely Moreno, Sarah Branch, and Naila Thevenot

[CLIP model (Contrastive Language-Image Pre-training)](https://openai.com/research/clip)
[Vizwiz dataset](https://vizwiz.cs.colorado.edu/VizWiz_visualization/view_dataset.php)
[React Native](https://reactnative.dev/)
