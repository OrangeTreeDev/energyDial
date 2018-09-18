# Energy Dial

A energy dial which shows the car electric quantity and charge status, implemented with JavaScript canvas API.

## Main features

1. support electric quantity change animation
2. support energy donut change animation
3. support charge status change with no animation

## Use

```javascript
carEnergyDial.fromValue = 10; // init electic quantity
carEnergyDial.targetValue = 100; // target electric quantity
carEnergyDial.timeStamp = Date.now(); // animation start time
carEnergyDial.changeEnergyWithAnimation(); // execute the animtion with default duration 1000ms
```

## Learn

[Canvas](https://developer.mozilla.org/en-US/docs/Web/API/Canvas_API)

## Screen shot

![electric quantity change animation](https://github.com/OrangeTreeDev/energyDial/blob/master/screen.gif)