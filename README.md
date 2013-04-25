ScreenSize
==========

a ScreenSize object for Cascades.

Just include the following in your c++ code when setting up your qml root...

#include "ScreenSize.hpp"
    ScreenSize* screenSize = new ScreenSize(this);
    qml->setContextProperty("ScreenSize", screenSize);

You will also want to link against -lbbdevice

aha!
