# Ransomware_Detector
Safe browsing facility that detects ransomware in the pre-encryption execution step without imposing any danger to host instance.

## How to Run


1. Please Download our code from GitHub
2. Go to "Extensions" in "More tools" menu under three dots in upper right corner of Chrome Browser
3. Activate Developer mode
4. Click on "Load unpacked" in the upper left corner
5. Select folder called "Ransomtect" of unpacked downloaded code
6. Click on puzzle icon in the upper right corner and Pin Ransomtect extension 
7. Click on Ransomtect icon, add your email: this way we will keep communication on safety of downlaoding files 
8. You're good to go! Now, whenever you download anything from web it will be automatically blocked and analysed by our AI.
9. The final step is to send a report containing the probability and download link of the file to the user's email (Note: This feature is not yet fully ready, we are working on it, hence as of now user will not be able to get the report on his email)

Please refer to visual guide in the bottom of the page.


## Machine Learning models we considered
* Random forests and other variations
* Artificial Neural Network
* Naïve Bayes
* K-nearest neighbors
* Gradient Boosting: XGBoost, AdaBoost, LightGBM, CatBoost
* SVM
* Stacking/Blending models
* LSTM (sequential data)

On top of classification algorithms, as there’s a severe shortage of available ransomware samples online, we will have to deal with imbalanced classification using techniques such as SMOTE (Synthetic Minority Oversampling Technique) as well as bagging and boosting 
techniques for imbalanced data.

We also intend to try clustering algorithms to check whether we can identify clusters of malware types, other than ransomware, such as : Worms, Trojans, Spyware, RATs, Stealers, Bankers etc.

## Stack
* Python,
* Pandas, SkLearn, TensorFlow, Keras, Numpy, MatplotLib
* Selenium, Beautiful Soup,
* AWS,
* BOTO3.

## Visual Guide
1. Please download our code from Github and follow instructions below
2. ![1 Screenshot 2021-07-10 at 09 34 11](https://user-images.githubusercontent.com/42537931/125157500-aae7cb80-e16b-11eb-93a2-58d79ae42a1a.png)
3. ![2  Screenshot 2021-07-10 at 09 34 59](https://user-images.githubusercontent.com/42537931/125157503-b1764300-e16b-11eb-8926-bd5794f0ea2c.png)
4. ![3  Screenshot 2021-07-10 at 09 35 26](https://user-images.githubusercontent.com/42537931/125157507-bcc96e80-e16b-11eb-993a-dced96f68323.png)
5. ![4  Screenshot 2021-07-10 at 09 35 51](https://user-images.githubusercontent.com/42537931/125157515-c8b53080-e16b-11eb-9bc1-c2d6fb4fd6a1.png)
6.
![5  Screenshot 2021-07-10 at 09 36 12](https://user-images.githubusercontent.com/42537931/125157527-d074d500-e16b-11eb-8a5f-f7f4d50592bc.png)
7. You're good to go! Enjoy your safe browsing!
   
![6  Screenshot 2021-07-10 at 09 39 11](https://user-images.githubusercontent.com/42537931/125157543-e387a500-e16b-11eb-8e7f-24cabc34a57f.png)

9. Note that you will be receiving emails in this format:

![MicrosoftTeams-image (9)](https://user-images.githubusercontent.com/42537931/125157713-c99a9200-e16c-11eb-8332-f8ce8bfee102.png)
 




