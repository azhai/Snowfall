Snowfall js
======================

Version 1.8.0 Jan 7th 2016
-------------------------

values for snow options are

```JavaScript
flakeCount,
flakeColor,
flakeIndex,
minSize,
maxSize,
minSpeed,
maxSpeed,
round, 		true or false, makes the snowflakes rounded if the browser supports it.
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
        image : "images/flake.png",
        minSize: 10, maxSize:32,
        riseUp: true,
        blocks: [
            {'left': 10, 'right': 30},
            {'left': 70, 'right': 90}
        ]
        });
```