# ASLI
American sign language Interpreter using Leap Motion Controller

It empower the speak disabled people to communicate through sign language with the people who doesnt understand sign language.
The Project recognises the sign language and outputs it in form text and sound.Such that the person who couldn't understand sign language can communicate with the speak disabled people freely.

Hardware Required:
Leap Motion Sensor
https://www.leapmotion.com/

Software:
AWS Machine Learing API.

1. Constructed 60,000 instance of Leap motion featured data of 11 sign symbol of ASL(America Sign Language) to produce a dataset.
2. Used that dataset to train our AWS ML Model,which uses the multinomial logistic regression to classify the multiclass data.
3. On Running the app.py, real time data(the hand gesture feed) are recognised through the ML Model.
4. Return the Result

![screen shot 2017-11-19 at 6 48 34 am](https://user-images.githubusercontent.com/17843556/34924728-17deb7f6-f973-11e7-8f94-35dd3bfe9099.png)


![screen shot 2017-11-19 at 10 41 18 am](https://user-images.githubusercontent.com/17843556/34924834-cbc75ca0-f973-11e7-8eed-f078b6562af8.png)
