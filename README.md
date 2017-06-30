# Android Things Projects
This is the code repository for [Android things Projects](https://www.packtpub.com/hardware-and-creative/android-things-projects?utm_source=repository&utm_medium=github&utm_campaign=repository&utm_term=9781787289246). It contains all the supporting project files necessary to work through the book from start to finish.

## About the Book
With this book, you will be able to take advantage of the new Android framework APIs to securely build projects using low-level components such as sensors, resistors, capacitors, and display controllers. This book will teach you all you need to know about working with Android Things through practical projects based on home automation, robotics, IoT, and so on. We’ll teach you to make the most of the Android Things and build enticing projects such as a smart greenhouse that controls the climate and environment automatically. You’ll also create an alarm system, integrate Android Things with IoT cloud platforms, and more.


## Instructions and Navigation
All of the code is organized into folders. Each folder starts with a number followed by the application name. 

The code will look like the following:
```
 int setStripColor(String command) {
 Serial.println("Color strip function...");
 struct data value = parseCommand(command);
 debugData(value);
 fillStrip(strip.Color(value.r,value.g,value.b),
 value.wait, value.dir);
 return 1;
 }

```

## Related Products
* [Smart Internet of Things Projects](https://www.packtpub.com/hardware-and-creative/smart-internet-things-projects?utm_source=repository&utm_medium=github&utm_campaign=repository&utm_term=9781786466518)

* [Cardboard VR Projects for Android](https://www.packtpub.com/application-development/cardboard-vr-projects-android?utm_source=repository&utm_medium=github&utm_campaign=repository&utm_term=9781785887871)

* [Raspberry Pi Android Projects](https://www.packtpub.com/hardware-and-creative/raspberry-pi-android-projects?utm_source=repository&utm_medium=github&utm_campaign=repository&utm_term=9781785887024)

### Suggestions and Feedback
[Click here](https://docs.google.com/forms/d/e/1FAIpQLSe5qwunkGf6PUvzPirPDtuy1Du5Rlzew23UBp2S-P3wB-GcwQ/viewform) if you have any feedback or suggestions. 
