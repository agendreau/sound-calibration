# Sound Sensor Calibration

## Introduction 
Create a program that can calibrate the sound sensor. ``||basic: Show||`` the ``||gatorMicrophone:sound||`` on the micro:bit. Hint: you can make the sensor more sensitive by changing the ``||gatorMicrophone: gain||``: the higher the gain the more sensitive the microphone is to changes in sound. The gain defaults to 2. After you think you've figured it out, ``|Download|`` the code and test it out. 

```blocks
input.onButtonPressed(Button.A, function () {
    gatorMicrophone.setGain(GainOptions.Eight)
    basic.showNumber(gatorMicrophone.getSoundIntensity())
})
```

```package
gatorMicrophone=github:sparkfun/pxt-gator-microphone
```
