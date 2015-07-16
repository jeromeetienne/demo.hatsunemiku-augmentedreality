
# Hatsune Miku Dancing in Augmented Reality

This demo shows hatsune miku dancing in augmented reality within 
your browser! This is great and surprisingly easy to do.
All that running on your browser, based on web standards.
Best of all, it even run on mobile phone if it 
supports WebGL and WebRTC.

I did it to show it was possible to do AR within the browser and to share the code to see what you guys can do with it. Below is a screenshot made on a nexus.

![screenshot](https://raw.githubusercontent.com/jeromeetienne/demo.hatsunemiku-augmentedreality/master/images/screenshot-nexus9.png)

If you want to play with this kind of things,
checkout [threex.webar](https://github.com/jeromeetienne/threex.webar),
the three.js extensions to make augmented reality on the web.


# How To Run The Demo ?
- put a browser on http://jeromeetienne.github.io/demo.hatsunemiku-augmentedreality
- it will read your webcam using [getUserMedia](https://developer.mozilla.org/en-US/docs/Web/API/Navigator/getUserMedia)
  - if it asks for permission, allow it :)
- it will recognize the marker you put in front of the mcamera
  - get the marker from [here](http://jeromeetienne.github.io/threex.webar/demo.hatsunemiku-augmentedreality/image-marker-265.html)
  - you can print it and point the camera toward the paper
  - or you can load the marker web page and put the phone in front of the camera

# Notes
- andra to write a blabla on the historical context
  - find below possible lines
  - wow look at what you can do in AR. it is great 
  - I did this with just a marker 
  - I did this for the DAQRI hackathon 
  - It is great! Hatsune miku in three.js dancing in AR 

- explain where Hatsune miku code is coming from
  - hasune miku wikipedia link. find cool video on youtube.
    - https://www.youtube.com/watch?v=pEaBqiLeCu0 
    - hatsune miku is no stranger to augmented reality
    - here you can see her doing a live concert.
    - well her hologram doing it
    - so it is a hologram of a virtual girl singing with the voice of a computer
    - futuristic enough :)
  - blabla on superhoge
    - the code to handle hatsune miku if from 
      [Takahiro Aoyagi](https://www.linkedin.com/pub/takahiro-aoyagi/96/10a/41a)
    - he is doing excelent work. 
    - you can find him on twitter as [@superhoge](https://twitter.com/superhoge).
    - Be sure to check out his [github](https://github.com/takahirox).
    - He did a [fork on three.js](http://github.io/takahirox/three.js) 
    - it may be included in three.js soon.
    - Here is his [example for three.js](http://takahirox.github.io/three.js/examples/#webgl_loader_mmd)
    - there is a very nice version in pure webgl (TODO find link) too
