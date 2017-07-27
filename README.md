The Matrix raining code effect implemented in various formats and across various libraries. I've excluded PhaserJS because it's my understanding that it uses Pixi.js for rendering so the Pixi.js examples should represent PhaserJS as well.  

Press F11 then F5 for full sreen effect in Chrome and Firefox.

## The Matrices

- [jquery-matrix.html](jquery-matrix.html) - [jQuery](https://jquery.com/) rendering using HTML DOM  
- [p5-matrix.html](p5-matrix.html) - Using [P5.js](https://p5js.org/)  
- [paperjs-matrix.html](paperjs-matrix.html) - Using [PaperJS](http://paperjs.org/)  
- [pixi-matrix.html](pixi-matrix.html) - Using [Pixi.js](http://www.pixijs.com/) for rendering   

I've tried to implement options via url parameters, for example:  
- [p5-matrix.html?maxchars=60](p5-matrix.html?maxchars=60)  
- [pixi-0101.html?maxshadowlength=28](pixi-0101.html?maxshadowlength=28)  
- [pixi-matrix.html?maxchars=40&maxshadowlength=32](pixi-matrix.html?maxchars=40&maxshadowlength=32)  
- [jquery-matrix.html?maxchars=40&maxshadowlength=24](jquery-matrix.html?maxchars=40&maxshadowlength=24)  

## Extras
- [pixi-0101-blue.html](pixi-0101-blue.html) - Special binary matrix in blue using [Pixi.js](http://www.pixijs.com/)  
- [pixi-0101.html](pixi-0101.html) - Binary matrix in red and blue using [Pixi.js](http://www.pixijs.com/)  
- [p5-dot-matrix.html](p5-dot-matrix.html) - Special dot matrix using [P5.js](https://p5js.org/)  

## Notes

There are various ways to achieve this effect across various libraries. I've tried to avoid is destroying objects, which can lead to a sub-optimal experience in JavaScript. I tried to create the base number of objects needed and simply move them to the top of the display once they pass the display height. In most cases so far, I ended up going the eaier route though, simply creating and deleting objects as needed.  

Source code: [https://github.com/Ugotsta/enter-the-matrices/](https://github.com/Ugotsta/enter-the-matrices/)
