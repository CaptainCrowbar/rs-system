# System Library

By Ross Smith

_[GitHub repository](https://github.com/CaptainCrowbar/rs-system)_

## Overview

```c++
#include "rs-system.hpp"
namespace RS::System;
```

This is my library of operating system related code.

The CMake file includes an `install` target to copy the library into
`/usr/local/{bin,include}` or the equivalent. Headers can be included
individually as required, or the entire library can be included using
`"rs-system.hpp"`.

Other libraries required:

* [PCRE2](http://www.pcre.org/)
* [My I/O library](https://github.com/CaptainCrowbar/rs-io)
* [My formatting library](https://github.com/CaptainCrowbar/rs-format)
* [My regex library](https://github.com/CaptainCrowbar/rs-regex)
* [My template library](https://github.com/CaptainCrowbar/rs-tl)
* [My unit test library](https://github.com/CaptainCrowbar/rs-unit-test)

## Index

* [Dynamic libraries](dso.html)
* [Version information](version.html)
