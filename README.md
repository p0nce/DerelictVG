DerelictVG
==========

A dynamic binding to [OpenVG](http://www.khronos.org/openvg) for the D Programming Language.

This does not include bindings to [EGL](https://www.khronos.org/egl) though! For now its only usable with [AmanithVG](http://www.amanithvg.com/).

Please see the pages [Building and Linking Derelict](http://derelictorg.github.io/compiling.html) and [Using Derelict](http://derelictorg.github.io/using.html), or information on how to build DerelictVG and load the OpenVG library at run time. In the meantime, here's some sample code.

```D
import derelict.openvg;

void main() {

    DerelictVG.load("libOpenVG.dll");
    // Now OpenVG functions can be called.
    ...
}

```
