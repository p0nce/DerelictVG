DerelictVG
==========

A dynamic binding to [OpenVG](http://www.khronos.org/openvg) for the D Programming Language.

This does not include bindings to [EGL](https://www.khronos.org/egl) though.

For information on how to load an OpenVG library via DerelictVG, see the page [DerelictUtil for Users](https://github.com/DerelictOrg/DerelictUtil/wiki/DerelictUtil-for-Users) at the DerelictUtil Wiki. In the meantime, here's some sample code.

```D
import derelict.openvg;

void main() {

    DerelictVG.load("libOpenVG.dll");
    // Now OpenVG functions can be called.
    ...
}

```
