# NativeScript Game App
This repository demonstrates how to create games such as Flappy Bird inside NativeScript Angular.

#### Technologies
- NativeScript Angular - {N} 6
- Model-Driven Objects
- Custom Animation Implemenations

## Getting Started
1. Download or clone this repository.
2. Install dependencies `npm i` or `npm install`.
3. Install and run your desired runtime `tns run ios` or `tns run android`.

### Known Issues
- Android `background-position` support is incomparable to iOS. Temporarily have disabled the bird animation on Android as it cannot handle the sprite animation.
- Android player sensitivity is off - most likely need to account for DPI for calculations.

### App Images

|iOS|Android|
|:---:|:---:|
|<img alt="screen shot 2017-08-26 at 3 37 08 pm" src="https://media.giphy.com/media/3oKGzDdpiS6g2ULQCQ/giphy.gif">|<img src="https://media.giphy.com/media/l4Fsoa4XMDbSm3zUs/giphy.gif">|

# Original Nativesciprt Flappy Bird
(https://github.com/sean-perkins/nativescript-flappy-bird)
