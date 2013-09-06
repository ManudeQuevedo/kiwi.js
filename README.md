Kiwi.js (BETA)
=====



###HTML5 game library written in TypeScript/Javascript
-----------------------------------------------------------------

version 0.4.9


###Aim

* An opensource TypeScript/Javascript library for game creation
* Targeting native mobile apps  as well as both desktop and mobile browsers
* Future focussed
* WebGL and 2D Canvas rendering
* Support for Cocoon.js as a native mobile app deployment solution 

###License

* GPL 2

###Features

These features are either currently supported or very close to being supported. Many more features are in the pipeline.

* State Management
* Extensible game objects (such as sprites)
* Entity/Component system
* 2D Canvas and WebGL rendering (experimental)
* Target Cocoon.js (experimental)
* Full nested display list
* HTML5 HUD
* Tween Engine (based on Tween.js)
* Signals
* Spritesheets, Texture Atlases and Tilemaps
* Multitouch support
* Geometry Utilities
* Plugin System
* Arcade Physics
* File Management and loading
* Clocks and Timers

###RoadMap

Within the next few weeks

* API documentation
* Improved build support (grunt)
* Lots of examples
* Many bug fixes and improved robustness

Within the next few months

* Plugins and products
* Much optimisation

###Build

Kiwi.js is currently using Typescript 9.0.1
Either - use Visual Studio/TS extension. There are csproj files for both the main project and also the examples.
Or - use the grunt file. This requires installing node.js, and the grunt CLI package. 

The csproj and grunt compilation methods both output a single kiwi.js file in /build
Grunt will also create a min.js version and also output a kiwi.d.ts definition file in /build as well
Shortly there will be further grunt options for dev builds and for compiling the documentation using YUIDoc


###Contribution

We'd love you to get involved in making the Kiwi.js library. If you'd like to contribute please get in touch, clone the repo and have a dig around. Full contributor guidelines will be here soon along with detailed build instructions.