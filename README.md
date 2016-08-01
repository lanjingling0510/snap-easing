## Snap SVG Easing Equations

    A port of Robert Penner’s equations to percentage-based formulas for use in Snap SVG.


Available methods:
- Quad ( mina.easeInQuad, mina.easeOutQuad, mina.easeInOutQuad )
- Cubic ( mina.easeInCubic, mina.easeOutCubic, mina.easeInOutCubic )
- Quart ( mina.easeInQuart, mina.easeOutQuart, mina.easeInOutQuart )
- Quint ( mina.easeInQuint, mina.easeOutQuint, mina.easeInOutQuint )
- Sine ( mina.easeInSine, mina.easeOutSine, mina.easeInOutSine )
- Circ ( mina.easeInCirc, mina.easeOutCirc, mina.easeInOutCirc )
- Expo ( mina.easeInExpo, mina.easeOutExpo, mina.easeInOutExpo )
- Elastic ( mina.easeInElastic, mina.easeOutElastic, mina.easeInOutElastic )
- Back ( mina.easeInBack, mina.easeOutBack, mina.easeInOutBack )
- Bounce ( mina.easeInBounce, mina.easeOutBounce, mina.easeInOutBounce )

## Example use:
```javascript
  var canvas = Snap('#svg');
  var circle = canvas.circle( 0, 0, 100 ).attr({ fill: '#ff0000' });
  circle.animate({ cx: 100 }, 1000, mina.easeOutExpo);


```

## Easing function legend


![image](./.github/image-1)

## Reference
- [http://www.robertpenner.com/easing/
http://snapsvg.io
](http://www.robertpenner.com/easing/
http://snapsvg.io
)

- [http://snapsvg.io](http://snapsvg.io)
