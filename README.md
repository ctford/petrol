# Petrol

Petrol is a library for building ClojureScript pages, using an event-stream
model.

[![Clojars Project](http://clojars.org/petrol/latest-version.svg)](http://clojars.org/petrol)

[![Build
Status](https://travis-ci.org/krisajenkins/petrol.svg?branch=0.1.0)](https://travis-ci.org/krisajenkins/petrol)

## About

Documentation in on its way. In the meantime, my [talk at ClojureExchange 2015](https://skillsmatter.com/skillscasts/7227-clojurescript-architecting-for-scale)
will tell you all you need to know.

## Running the examples

``` sh
cd examples
lein figwheel counter counter2 spotify hydra
```

Then open http://localhost:3449

## Issues

If you get this exception when running `lein`:

``` sh
clojure.lang.Compiler$CompilerException: java.io.FileNotFoundException: Could not locate cljs/analyzer__init.class or cljs/analyzer.clj on classpath: , compiling:(figwheel_sidecar/utils.clj:1:1)
```

Try upgrading leiningen to version 2.5.3+

``` sh
lein upgrade
```

## License

Copyright © 2015 Kris Jenkins

Distributed under the Eclipse Public License either version 1.0 or (at
your option) any later version.
