# MBAS <small>(alpha)</small> - Middleman 4 + Bootstrap 4 + Angular + Sass

#### Middleman environment with Bootstrap 4 Alpha for layout, Angular to handle the data binding, routing and general UX, and Sass to enhance the developer experience at the moment of coding.

Main components:
* [Middleman 4](https://middlemanapp.com/)
* [Bootstrap 4 Alpha](http://v4-alpha.getbootstrap.com/)
* [AngularJS](https://angularjs.org/)
* [Sass](http://sass-lang.com/)

**Important:** Make sure you have installed:
* [Ruby](https://www.ruby-lang.org/en/documentation/installation/#package-management-systems)
* [Node](https://nodejs.org/en/)
* [Middleman](https://middlemanapp.com/)
* [Bundler](http://bundler.io/)
* [Bower](http://bower.io/)
* [Sass](http://sass-lang.com/install)

## Installing process

Download the repository and execute:

```
$ bower install
$ bundle install
$ bundle exec middleman
```

**Once you run the project you will have access to an environment with multiple assets from Sass, Bootstrap 4, custom Angular components and more. Get into it to read the full documentation**

If you have this error while installing Middleman:

```
make "DESTDIR=" clean

make "DESTDIR="
compiling binder.cpp
In file included from binder.cpp:20:
./project.h:116:10: fatal error: 'openssl/ssl.h' file not found
#include <openssl/ssl.h>
         ^
1 error generated.
make: *** [binder.o] Error 1

make failed, exit code 2
```

just execute `bundle config build.eventmachine --with-cppflags=-I/usr/local/opt/openssl/include`. The issue is 
related with Mac OSX "El Capitan"

## Sections within the project starter:
* Welcome/Intro page
* Sass documentation
* Form elements (Angular custom directives)
* Environment (OS/Browser) detection
* Parallax layouts
* Securebox modules (sensitive content to be loaded only on demand)

## TO DO <small>2016/04/11</small>:
* Build process: fix and test output | DONE
* Finish internal documentation
* Add multiple sort of transitions in between loading views
* Minor other fixes
* Extend project starter beyond!