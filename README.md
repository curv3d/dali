# dali

**Dali** is a new kind of graphics API built on top of WebGPU.

Dali is a high performance graphics API that runs on modern GPUs.
Thanks to WebGPU, it is cross-platform, running either in a web browser
using WASM, or running natively on Windows, Linux, MacOS, Android and iOS.

Dali is a hybrid 2D/3D graphics API that goes far beyond the postscript/SVG 2D graphics model.
It is extensible. Instead of being restricted to a fixed set of graphics primitives (as in SVG),
you can define new primitives procedurally, as operations on signed distance fields.
So in addition to SVG primitives, you can also define fractals, non-affine transformations
such as twist and bend, and graphics combinators such as blending and morphing, or
any of the effects seen on [ShaderToy.com](https://shadertoy.com/).

Using Dali, there are no limits to what a graphical user interface can look like.
You aren't boxed in by the SVG 2D rendering model or by what HTML/CSS can render.
