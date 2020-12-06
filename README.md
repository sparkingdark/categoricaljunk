<img src = "https://challengepost-s3-challengepost.netdna-ssl.com/photos/production/software_thumbnail_photos/001/303/587/datas/medium.png" style="width:256px;height:256px;"></img>

# Categorical Trash


## Inspiration
Environment is the most important part of our life and we humans are producing so much trash that mother earth is now polluted so much that we need some good innovation to fight this and solve the problem.That's why we come with categorical trash,an android app.


## What it does

It basically a very simple application which takes picture from the users phone camera and after that it differentiate the type of the junk in various categories like metal,glass,biodegradable,plastic and cardboard.You got a link after that which give you the good reference what to do with the trash.

## How we built it

We basically search for some similar opensource code to reuse in our application,so we found the android app from the github and we train a model from the google colab and [teachablemachine](https://teachablemachine.withgoogle.com/).Now we collected data from the [trashnet](https://drive.google.com/drive/folders/0B3P9oO5A3RvSUW9qTG11Ul83TEE).After that we get the tflite model and embedded into our application to run it.Voila it's works awesome.

## Challenges we ran into

- first challenge is to get data and we fill that we lack of data.
- Time constraint to train a model.
- Getting ready with sceleton application to make our demo work.

## Accomplishments that we're proud of

- We built it within 18 hours and now going to improve it more.
- Our team worked together and created this awesome application this far.

## What we learned
- Machine Learning with tflite
- Android app development using Kotlin
- Some basic UI design


## What's next for Categorical trash

- Adding more functionality
- Publishing it to the play store
- Getting feedback from users to improve.

## Meet our Team

- [Debojyoti Chakraborty]()
- [Peter hankyu wi](https://https://www.linkedin.com/in/peter-hankyu-wi/)
- [Shubham Patel](https://www.linkedin.com/in/shubham-patel-88978217b)
- [Ajay Gour]()

## Credits Open Source Code Used:

- [Anti Plasti](https://github.com/antiplasti/Plastic-Detection-Model) 
  License Granted [MIT](https://github.com/antiplasti/Plastic-Detection-Model#license)
  
- [Plant Disease Detector](https://github.com/obeshor/Plant-Diseases-Detector) for skeleton app
  License Granted [Apache 2.0](https://github.com/obeshor/Plant-Diseases-Detector#license)
  
- [Teachable machine](https://teachablemachine.withgoogle.com/)
