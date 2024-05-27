# Deep Learning for Diabetic Eye Disease: A Comparative Analysis of Detection
and Grading Models

Diabetic retinopathy stands as a significant microvascular
complication of diabetes mellitus, impacting millions with
health on a global scale (Stitt et al. 2016). Diabetes mellitus
harms multiple organ systems, but the eyes are particularly
vulnerable to its effects. Diabetic retinopathy emerges as
a degenerative affliction of the retina, marked by the
rapid erosion of visual acuity. Its onset often precedes
other complications, meaning that early detection in retina
images can prevent further health complications.

Because of its importance and relevance, we chose to
study detecting diabetic retinopathy in retina images. New
advanced deep learning models are known to be useful
in image classification tasks, so we decided to focus our
project at this intersection.

Our project compares the performance of VGG16, DenseNet, ResNet50, 
and AlexNet in classifying retina images from the Asia Pacific Tele-Ophthalmology Society (APTOS) 
dataset that has labels made by clinicians on diabetic retinopathy status.  

All models were trained for 10 epochs.  We utilized Tensorflow's pre-trained models and modified 
each to suit the needs of our task.  We considered accuracy, loss, and run
time when evaluating model performance on our dataset.

![image](https://github.com/ernraff/Diabetic_Retinopathy/assets/103540977/afd5ed76-5850-4009-a374-9a229e7b25e2)

We determined that VGG16, with the highest accuracy rate, was the best performing of the models evaluated.
