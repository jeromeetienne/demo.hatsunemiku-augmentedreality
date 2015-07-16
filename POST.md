
# Hatsune Miku Dancing in Augmented Reality

This demo shows hatsune miku dancing in augmented reality within 
your browser! This is great and surprisingly easy to do.
All that running on your browser, based on web standards.
Best of all, it even run on mobile phone if it 
supports WebGL and WebRTC.

I did it to show it was possible to do AR within the browser and to share the code to see what you guys can do with it. Below is a screenshot made on a nexus.

![screenshot](https://raw.githubusercontent.com/jeromeetienne/demo.hatsunemiku-augmentedreality/master/images/screenshot-nexus9.png)


# How it it coded ?

It is mainly a link of 2 parts. 
First [webar extensions](https://github.com/jeromeetienne/threex.webar)
for three.js. They bundle what needed to handle augmented reality with three.js. from the webcam setup to the marker localisation.
Second part is the [mmd loader](http://takahirox.github.io/three.js/examples/#webgl_loader_mmd) which load the model. It load the hatsune miku model and its animations.
TODO put the superhoge blabal here

Once you got those 2 parts, things are simple :) you just have to display your model where your marker is. 
To know the tech details, you will have to dig in [the](http://takahirox.github.io/three.js/examples/#webgl_loader_mmd)
[code](https://github.com/jeromeetienne/threex.webar).
I will likely talk more about AR tho. 

# Now Let's Do a Bit of History
I did this to show it was possible to do AR within the browser and to share the code to see what you guys can do with it. 
It was for a [AR oriented hackathon](http://daqri.com/dublinhacks/) in dublin.
It recently landed a [new job](https://twitter.com/jerome_etienne/status/572435641079877632) at [Daqri](http://daqri.com). Part of my job is developer relation, so i get to help people doing AR. i love it :)


All the code to handle hatsune miku is from 
[Takahiro Aoyagi](https://www.linkedin.com/pub/takahiro-aoyagi/96/10a/41a).
He did a [fork on three.js](http://github.io/takahirox/three.js) to load mmd formats, the format used to store hatsune miku.
It may be included in three.js soon.
Here is his [example for three.js](http://takahirox.github.io/three.js/examples/#webgl_loader_mmd)
It all started by his [mmd viewer](http://takahirox.github.io/mmd-viewer-js/) in pure webgl.. 
The original contains a LOT of neat features like inverse kinetic, physics for the hair,
a toon shader to make the color more cartoonish, a edge shader to enhance the outline of the model 
like a drawing.
He is doing excelent work. Check him out on twitter as [@superhoge](https://twitter.com/superhoge).

Let's have a word about [Hatsune Miku]() herself.
It is such a nice story. 
She is a japanese star but she is purely virtual.
She is a humanoid persona which appears as drawing or as hologram. 
There is no human behind, even for the voice!
When she sings, what you hear is a voice synthetiser from [crypton](https://en.wikipedia.org/wiki/Crypton_Future_Media)

She even do [concerts](https://www.youtube.com/watch?v=pEaBqiLeCu0) where thousand of fans are going. 
Actual human fans i mean, not virtual ones.
As you can see, hatsune miku is no stranger to augmented reality.
I love her!

# How To Run The Demo ?

You may want to run this demo obviously,
Here is how to do it.
First you put the [demo url](http://jeromeetienne.github.io/demo.hatsunemiku-augmentedreality) in your browser.
It will read your webcam using [getUserMedia](https://developer.mozilla.org/en-US/docs/Web/API/Navigator/getUserMedia). When it asks for permission, allow it :)
Then you need to put this [AR marker](http://jeromeetienne.github.io/threex.webar/demo.hatsunemiku-augmentedreality/image-marker-265.html) in front of the camera. 
You can print it and point the camera toward the paper
or you can load the marker web page and put the phone in front of the camera

And now you can see Hatsune Mike Dancing in Augmented Reality

# Conclusion
If you want to experiment with augmented reality and three.js, checkout [threex.webar](https://github.com/jeromeetienne/threex.webar).
It is so cool to make augmented reality on the web!
I hope you have as much fun as me doing it :)
I can't wait to see what augmented reality can do on mobile's browsers.

That's all folks, have fun.
