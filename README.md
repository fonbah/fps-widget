fps.js
========

#### JavaScript widget to display current FPS ####

Javascript widget to display current perfomance based upon FPS in browser
It`s very lightweight and scallable, may be used somewhere else than your dev workspace.

Work in internet explorer not supported,
unless ie will be upgraded to needed standards in next versions,  but who cares?)

### Usage ###

Download script in your html first
<script src="fps.min.js" type="text/javascript"></script>

and start using ...
```javascript
var fps = new FPS({w: 400}); //@param w property - width of widget in pixels
fps.start();

OR

fps.start();

// Your code here

fps.stop();
```