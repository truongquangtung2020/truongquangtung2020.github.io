Hash is a rewrite of [Tosh](http://tosh.tjvr.org/), text-based Scratch project editor.
This version is open-source, with a readable, modern codebase.


Dependencies
============

Thanks for @tjvr for the project!

Current status
==============

* Load/save seems to work
* Importing / compiling scripts is there, but needs extensive testing & improvement
* Measuring scripts is fully implemented & tested (so we can "clean up" when saving to sb2) 
* Playing projects seems to work

* No sprite management
* No costume management (nor am I particularly interested in adding this!)
* Highlighting almost works
* Completion is in-progress but goodness it's a difficult problem

Running
=======

```sh
git clone --recursive https://github.com/tjvr/tosh2
cd tosh2
echo ';window.P = P' >> phosphorus/phosphorus.js
yarn
yarn grammar && yarn test
yarn start
```

<http://localhost:8080/app/>

If someone wants to set up browserify/babelify for bundling, that would be excellent

