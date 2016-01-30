Snowfall js
======================

Version 1.8.0 Jan 7th 2016
-------------------------

values for snow options are

```JavaScript
image,
background,
flakeCount,
flakeColor,
flakeIndex,
minSize,
maxSize,
minSpeed,
maxSpeed,
leftDeg,
rightDeg,
colorful,		true or false
colorAlpha,		float, 0-1
rounded,		true or false, makes the snowflakes rounded if the browser supports it.
shadow		true or false, gives the snowflakes a shadow if the browser supports it.
riseUp		true or false
blocks		array of {'left': p1, 'right':p2}, 0<=p1<=p2<=100
```

Example Usage :

```JavaScript
snowFall.snow(elementCollection, {image : "images/flake.png", minSize: 10, maxSize:32});
```

-or-

```JavaScript
snowFall.snow(elementCollection, {
        background: 'images/love.jpg',
        minSize: 5, maxSize:20,
        minSpeed: 0.3, maxSpeed: 2,
        rounded: true,
        colorful: true,
        flakeColor: '#ffffff',
        colorAlpha: 0.5,
        riseUp: true,
        blocks: [
            {'left': 10, 'right': 30},
            {'left': 70, 'right': 90}
        ]
        });
```