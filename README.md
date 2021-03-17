# Yolov4_samruk_hackathon
During samruk hackathon 2021, I created a object detection model on yolov4 model, 
The model able to detect:
1. Workers
2. Safety jacket
3. helmet
4. No helmet

Use: It can be use to detect if the workers are following the safety rules or not and raise an flag(future implementation).
Data: We use very small dataset (collected from google images)consist ~130 images we used roboflow (https://app.roboflow.com/) to augment those images to increase our training dataset.
link: !curl -L "https://app.roboflow.com/ds/YCee8rDBdz?key=1lH93bQ5vU" > roboflow.zip; unzip roboflow.zip; rm roboflow.zip
Result: result on images were attached on the repo
video: https://drive.google.com/file/d/1UKqlj3nwvh6t2twx01ENLgVAMm6HMQW2/view?usp=sharing
