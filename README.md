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
- [Eido](https://github.com/leifericf/eido) Declarative data-driven graphics  ![][clj]
- [raycaster-demo](https://srdja.github.io/raycaster-demo/) Raycaster renderer in ClojureScript  ![][cljs]

See more Clojure repositories tagged with ["graphics"](https://phronmophobic.github.io/dewey/search.html?topic=graphics)

## Sound / Music / Media

- [Leipzig](https://github.com/ctford/leipzig) Music Composition ![][clj] ![][cljs]
- [Edna](https://github.com/oakes/edna) Making MIDI music with edn data ![][clj] ![][cljs]
- [Overtone](https://github.com/overtone/overtone) Based on Supercollider ![][clj]
- [clj-media](https://github.com/phronmophobic/clj-media) Read, write, and transform audio and video, powered by FFmpeg and clong ![][clj]
- [cljs-bach](https://github.com/ctford/cljs-bach) WebAudio API ![][cljs]
- [Web Audio Playground](https://clojurecivitas.org/scittle/audio/audio_playground.html) built with ClojureScript + Scittle

See more Clojure repositories tagged with ["sound"](https://phronmophobic.github.io/dewey/search.html?topic=sound) / ["music"](https://phronmophobic.github.io/dewey/search.html?topic=music)

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
- [Puck](https://github.com/lambdaisland/puck) Wrapper for Pixi.js (somewhat outdated) ![][cljs]
- [Arcadia](https://arcadia-unity.github.io/) Arcadia is the integration of the Clojure programming language and the Unity3D game engine. It brings a live coded, functional, dynamic Lisp to the industry standard cross-platform game development tool. ![][clr]

See more [Clojure repositories tagged with "game"](https://phronmophobic.github.io/dewey/search.html?topic=game)

### Engines

Underlying Java / JavaScript game engines, it can be interesting to look these
over, before evaluating Clojure/ClojureScript libraries that wrap them.

- [libgdx](https://libgdx.com/) Java 2D/3D ![][java]
- [lwjgl](https://www.lwjgl.org/) Java 2D/3D ![][java]
- [jaylib](https://github.com/electronstudio/jaylib) Java bindings for the popular C-based engine Raylib ![][java]
- [jMonkeyEngine](http://jmonkeyengine.org/) Java 3D ![][java]
- [pixi.js](https://www.pixijs.com/) JavaScript 2D WebGL ![][js]
- [Phaser](https://phaser.io/) JavaScript full-features framework ![][js]
- [Babylon.js](https://www.babylonjs.com/) JavaScript 3D engine ![][js]

### Open Source Games

- [Dandy Dungeon](https://github.com/jackpal/Dandy-Dungeon) A collection of implementations of a simple 2D dungeon crawling game, has a [Clojure](https://github.com/jackpal/Dandy-Dungeon/tree/master/dandy-clojure) and [ClojureScript](https://github.com/jackpal/Dandy-Dungeon/tree/master/dandy-clojurescript) version
- [Moon](https://github.com/damn/moon) Action RPG Game made with libgdx
- [selfsame's Clojure games](https://itch.io/c/57995/clojure-game-dev) A collection of over a dozen games made with Arcadia
- [The King](https://github.com/Clojure2D/clojure2d-examples/tree/master/src/games/the_king) Example game for Clojure2D
- [aMaze](https://narimiran.github.io/amaze/) Maze crawler game, playable in the browser. Made with Quil.
- [Wizard Masters](https://github.com/ertugrulcetin/wizard-masters) Multiplayer browser game made with ClojureScript and Babylon.js.
- [Galaga - ClojureScript & Scittle](https://clojurecivitas.org/scittle/games/galaga.html)
- [Asteroids - ClojureScript & Scittle](https://clojurecivitas.org/scittle/games/asteroids_article.html)
- [Memory Game - ClojureScript & Scittle](https://clojurecivitas.org/scittle/games/memory_game_article.html)
- [Raylib - Clojure](https://raylib-clj.b12n.app) - Port of Raylib examples to Clojure
- [Raylib - Jolt](https://raylib-jlt.b12n.app) - Port of Raylib examples to Jolt
- [Raylib - Jank](https://raylib-jnk.b12n.app) - Port of Raylib examples to Jank

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
[clr]: https://img.shields.io/badge/-ClojureCLR-8A2BE2
