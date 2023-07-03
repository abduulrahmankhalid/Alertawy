# Alertawy Testing Application
### Deep Learning Testing Application.

# Abstract
We developed a dedicated testing application to validate the accuracy of the deep learning monitoring system and evaluate each model's performance in providing accurate predictions.

After training and saving our custom deep learning models, we deployed them in our mobile testing application using TensorFlow Lite. This conversion process resulted in a slight drop in performance, but it wasn't a significant concern.
The mobile deep learning inference pipeline involves capturing an image from the front camera, preprocessing it, and feeding it into the models. We use the Google ML Kit face detection model to check for the driver's presence and monitor drowsiness. The gaze estimation model determines the driver's focus, while the distraction detection model identifies phone distractions.
The models are executed sequentially every second, with an average inference time of about 300 milliseconds on most devices.

Finding the right plugins for integrating TensorFlow Lite models into our Flutter application was a challenge, but we managed to overcome it. The result is a well-structured and robust deep-learning monitoring system for our mobile app.

#### For more information regarding Alertawy Testing App, please refer to the [documentation](https://github.com/abduulrahmankhalid/Alertawy/blob/main/Alertawy%20DMS%20Documentation.pdf).

# Alertawy Testing App UI

![6](https://github.com/abduulrahmankhalid/Alertawy/assets/76521677/593fd846-9cd7-4466-a823-b68e0e9d9f9b)


# Alertawy Testing App Full Demo


https://github.com/abduulrahmankhalid/Alertawy/assets/76521677/21186f44-2b2f-47eb-8cd9-9d6c034ab8af

