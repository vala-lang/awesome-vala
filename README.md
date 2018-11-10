# awesome-vala [![Awesome](https://awesome.re/badge.svg)](https://awesome.re)

 A curated list of awesome Vala libraries.

## Contents

- [Data Structures](#data-structures-&-data-types)
- [Graphic Libraries](#graphic-libraries)
- [GUI Programming](#gui-programming)
- [Multimedia Processing](#multimedia-processing)
- [XML & Data Serialization](#xml-&-data-serialization)
- [Templating](#templating)
- [Numerical Computation](#numerical-computation)
- [Web Development](#web-development)

## Data Structures & Data Types

- [Libgee](https://wiki.gnome.org/Projects/Libgee), an utility library providing GObject-based interfaces and classes for commonly used data structures (lists, maps, queues, trees, etc.).
- [Graphene](https://github.com/ebassi/graphene) is a thin layer of types for graphic libraries. It provides common types needed to handle 3D transformations: points, triangles, rectangles, quads, quaternions, vectors, matrices, spheres, etc.
- [Numeric-GLib](https://github.com/arteymix/numeric-glib) is a collection of numeric data types for GLib (and Vala) via GCC extensions. It includes 128 bit integers & floats, complex types, vectorized operations, and decimal types.

## Graphic Libraries

- [Cairo](https://cairographics.org/) is a 2D graphics library with support for multiple output devices. This is pretty much the default library you get in Vala.
- [SDL2](https://www.libsdl.org/) is a cross-platform development library designed to provide low level access to audio, keyboard, mouse, joystick, and graphics hardware via OpenGL, Direct3D, and Vulkan. Community bindings are available [here](https://github.com/sdl2-vapi/sdl2-vapi).
- [GRX](https://github.com/ev3dev/grx) is a graphics library for simple graphics displays (think 1-bit displays or Adafruit's PiTFT displays). It also includes keyboard, mouse, joystick and touchscreen input support.
- [GEGL](http://gegl.org/) is a data flow based image processing framework, providing floating point processing and non-destructive image processing capabilities. Think of it as "Reactive Programming for Images".
- [Babl](http://gegl.org/babl/) is a dynamic, any to any, pixel format translation library.

## GUI Programming

- [GTK+](https://www.gtk.org/) is the de facto library fro GUI development in Vala. Bindings are included with the vala compiler.

## Multimedia Processing

- [GStreamer](http://gstreamer.freedesktop.org/) is a powerful framework for creating multimedia applications.

## XML & Data Serialization

- [GXML](https://gitlab.gnome.org/GNOME/gxml/) is a GObject API for manipulating XML and a Serializable framework from GObject to XML
- [Json-GLib](https://gitlab.gnome.org/GNOME/json-glib/) implements a full JSON parser and generator using GLib and GObject, and integrates JSON with GLib data types.
- [libyaml-glib](https://github.com/rainwoodman/libyaml-glib) is the GLib binding of libyaml, plus a GObject builder that understands YAML

## Templating

- [Compose](https://github.com/arteymix/compose) is a functional templating library for Vala.
- [template-glib](https://gitlab.gnome.org/GNOME/template-glib) is a library for template expansion which supports calling into GObject Introspection from templates.

## Numerical Computation

- [vast](https://github.com/rainwoodman/vast) is a project for generative modelling in Vala. Think of TensorFlow rewritten in Vala.

## Crypto and Security

- [GnuTLS](https://www.gnutls.org/) is a secure communications library implementing the SSL, TLS and DTLS protocols and technologies around them. It provides a simple API to access the secure communications protocols as well as APIs to parse and write X.509, PKCS #12, and other required structures.

## Web Development

- [Valum](https://github.com/valum-framework/valum) is a Web micro-framework entirely written in Vala.
- [Ambition](https://github.com/AmbitionFramework/ambition) is a web framework written in Vala, with the MVC pattern in mind. Kinda unmaintained (someone could refactor it to use Valum under the hood, and maybe move it to Meson 😉)

## Contribute

Contributions welcome! Read the [contribution guidelines](contributing.md) first.

## License

[![CC0](http://mirrors.creativecommons.org/presskit/buttons/88x31/svg/cc-zero.svg)](http://creativecommons.org/publicdomain/zero/1.0)

To the extent possible under law, Mario Daniel Ruiz Saavedra and the other contributors have waived all copyright and
related or neighboring rights to this work.
