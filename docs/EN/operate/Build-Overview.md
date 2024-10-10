# Building Trio - Overview

There are two primary options for building Trio: building Trio using a web browser and GitHub and building Trio with Xcode on an Apple Mac computer. An overview of each build method, along with the associated build requirements, can be found below.

## Build Trio with GitHub  (i.e. “Browser Build”)
The complete requirements for building Trio using GitHub are summarised below.
* Trio can be built with a web browser using GitHub Actions.
* The app is then installed by you on your phone using the TestFlight app.
* As long as you use the same Apple Developer account, your app is the same regardless of the build
method. Therefore, settings and history are maintained when you install the app on your phone. Your
pump and CGM can remain attached.  

**Requirements**
* [Compatible Phone](…/Getting-Started/iphone.md).
* [Compatible CGM](…/Getting-Started/cgm.md).
* [Compatible Insulin Pump](…/Getting-Started/pump.md).
* [Free GitHub account](https://loopkit.github.io/loopdocs/browser/secrets/#new-github-account).
* [Paid Apple Developer account](https://loopkit.github.io/loopdocs/build/apple-developer/#switching-from-free-to-paid-memberships).

:::{important}
_When building Trio with GitHub, you must have a paid Apple Developer account._
:::  

To start building Trio with GitHub, visit [Build Trio with GitHub](…/operate/GH-Build.md).  

## Build Trio with Xcode (i.e., “Mac Build”)
The complete requirements for building Trio using Xcode are summarised below.
* Trio can be built on an Apple Mac computer using Xcode.
* Requirements are similar to building with GitHub. However, there are some additional requirements.
* As long as you use the same Apple Developer account, your app is the same regardless of the build
method. Therefore, settings and history are maintained when you install the app on your phone. Your
pump and CGM can remain attached.  

**Requirements**
* [Compatible Phone](…/Getting-Started/iphone.md).
* [Compatible CGM](…/Getting-Started/cgm.md).
* [Compatible Insulin Pump](…/Getting-Started/pump.md).
* [Free GitHub account](https://loopkit.github.io/loopdocs/browser/secrets/#new-github-account).
* [Apple Developer account](https://loopkit.github.io/loopdocs/build/apple-developer/#switching-from-free-to-paid-memberships).

**Additional Requirements**
* [Compatible computer](https://loopkit.github.io/loopdocs/build/computer/).
* [Xcode](https://loopkit.github.io/loopdocs/build/xcode-version/).

:::{important} 
_When building Trio with Xcode, you must rebuild Trio every seven days if you choose to use a free Apple Developer account._
:::  

To start building Trio with Xcode, visit [Build Trio with Xcode](.../operate/XC-Build.md).   




