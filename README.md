# Awesome Creative Clojure

[Clojure](https://clojure.org/) is a modern LISP for the JVM, with [many
dialects](https://github.com/clj-easy/clojure-dialects-docs) for other
platforms, including JavaScript, Go, Dart, C#/.NET, and C/native.

Its interactive programming style makes it a fantastic platform for creative
coding projects, including graphics, sound, and games.

This is an overview of some of the projects, libraries, and resources out there. Contributions welcome!

## Graphics

- [Quil](https://quil.info) Graphics and animation sketches, based on Processing ![][clj] ![][cljs]
- [th.ing/geom](https://github.com/thi-ng/geom) a comprehensive and modular geometry & visualization toolkit. WebGL, OpenGL, SVG. ![][clj] ![][cljs]
- [Iglu](https://github.com/oakes/iglu) Turning data into GLSL shaders for use by OpenGL and WebGL. By Zach Oakes, part of play-cljc. ![][clj] ![][cljs]
- [Membrane](https://github.com/phronmophobic/membrane)  A Simple UI Library That Runs Anywhere ![][clj] ![][cljs]
- [Clojure2D](https://github.com/Clojure2D/clojure2d) a library supporting generative coding or glitching, based on Java2D ![][clj]


## Sound / Music / Media

- [Leipzig](https://github.com/ctford/leipzig) Music Composition ![][clj] ![][cljs]
- [Edna](https://github.com/oakes/edna) Making MIDI music with edn data ![][clj] ![][cljs]
- [Overtone](https://github.com/overtone/overtone) Based on Supercollider ![][clj]
- [clj-media](https://github.com/phronmophobic/clj-media) Read, write, and transform audio and video, powered by FFmpeg and clong ![][clj]
- [cljs-bach](https://github.com/ctford/cljs-bach) WebAudio API ![][cljs]

## Game Dev

- [Quil](https://quil.info) Based on Processing  ![][clj] ![][cljs]
- [play-cljc](https://github.com/oakes/play-cljc) Based on LWJGL  ![][clj] ![][cljs]
- [cljbox2d](https://github.con/lambdaisland/cljbox2d) 2D physics engine, based on jBox2D (Clojure) and Planck.js (ClojureScript)  ![][clj] ![][cljs]
- [Play-clj](https://github.com/oakes/play-clj) Based on libGDX  ![][clj]
- [jme-clj](https://github.com/ertugrulcetin/jme-clj) Based on jMonkeyEngine ![][clj]
- [vybe](https://github.com/pfeodrippe/vybe) A data driven game-dev framework, uses Raylib ![][clj]
- [Chocolatier](https://github.com/alexkehayias/chocolatier) opinionated game library. Pixi.js, Howler.js, Entity-component system  ![][cljs]
- [Phzr](https://github.com/dparis/phzr) wrapper for the Phaser HTML5 game framework  ![][cljs]
- [play-cljs](https://github.com/oakes/play-cljs)  ![][cljs]
- [Puck](https://github.com/lambdaisland/puck)  ![][cljs]

### Engines

Underlying Java / JavaScript game engines, it can be interesting to look these
over, before evaluating Clojure/ClojureScript libraries that wrap them.

- [libgdx](https://libgdx.com/) Java 2D/3D ![][java]
- [lwjgl](https://www.lwjgl.org/) Java 2D/3D ![][java]
- [jaylib](https://github.com/electronstudio/jaylib) Java bindings for the popular C-based engine Raylib ![][java]
- [jMonkeyEngine](http://jmonkeyengine.org/) Java 3D ![][java]
- [pixi.js](https://www.pixijs.com/) JavaScript 2D WebGL ![][js]
- [Phaser](https://phaser.io/) JavaScript full-features framework ![][js]

### Resources

#### Talks

- [Zach Oakes - Making Games at Runtime with Clojure (Clojure/conj 2014)](https://www.youtube.com/watch?v=0GzzFeS5cMc)
- [Functional Game Engine Design for the Web - Alex Kehayias (Clojure/conj 2016)](https://www.youtube.com/watch?v=TW1ie0pIO_E&t=1495s)
- [play-cljc - A new way to make games with Clojure](https://www.youtube.com/watch?v=y6WpUdECwmA)


<!-- badge definitions -->
[clj]: https://img.shields.io/badge/-clj-blue
[cljs]: https://img.shields.io/badge/-cljs-yellow
[java]: https://img.shields.io/badge/-java-red
[js]: https://img.shields.io/badge/-js-yellow
