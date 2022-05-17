# PotatoLeafDeseaseClassification
Deep learning becomes the most exact and precise platform for the detection of plant disease. Here, I have mentioning the technique to detect the  Potato leaf diseases.
Potato crop ( Solanum tuberosum L ) is one of the most important vegitable crop grown globally.
The yield of potato is greatly hampered in quality and quantity by fungal blight diseases which pose a major threat to the global food security.
Late blight caused by Phytophthora infestans and early blight caused by Alternaria solani are the most devastating foliage diseases for potato crops.
In reality, the farmers presume such disorders by visualizing mainly the colour change in the potato leaves that is usually risky due to subjectivity and huge time consumption.
Here I’ve introducing a computational model that automatically detect such diseases rapidly and quantitatively even at its early phase.

The pre trained models used here is VGG16, VGG19, ResNet50, Mobilenet. The accuracies got are 92.86, 80.39, 73, 78 respectively.
The dataset I have used to train models is PlantVillage which is a benchmark dataset and it is available on kaggle.
VGG 16 got higher accuracy than others. I have fine tuned the model VGG16 then I got 95.6 accuracy.
