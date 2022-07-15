# Awesome Vala [![Awesome](https://awesome.re/badge.svg)](https://awesome.re)

[<img src="vala.svg" align="right" width="100">](https://wiki.gnome.org/Projects/Vala/)

 A programming language using modern high level abstractions without imposing additional runtime requirements, by leaning on GLib and GObject.

## Contents

- [Data Structures & Data Types](#data-structures--data-types)
- [Editor Plugins](#editor-plugins)
- [Language Servers](#language-servers)
- [Graphic Libraries](#graphic-libraries)
- [GUI Programming](#gui-programming)
- [Multimedia Processing](#multimedia-processing)
- [XML & Data Serialization](#xml--data-serialization)
- [Templating](#templating)
- [Numerical Computation](#numerical-computation)
- [Crypto & Security](#crypto--security)
- [Web Development](#web-development)
- [IoC and Dependency Injection](#ioc-and-dependency-injection)

## Data Structures & Data Types

- [Libgee](https://wiki.gnome.org/Projects/Libgee) - A utility library providing GObject-based interfaces and classes for commonly used data structures (lists, maps, queues, trees, etc.).
- [Graphene](https://github.com/ebassi/graphene) - A thin layer of types for graphic libraries. It provides common types needed to handle 3D transformations: points, triangles, rectangles, quads, quaternions, vectors, matrices, spheres, etc.
- [Numeric-GLib](https://github.com/arteymix/numeric-glib) - A collection of numeric data types for GLib (and Vala) via GCC extensions. It includes 128 bit integers & floats, complex types, vectorized operations, and decimal types.
- [United](https://github.com/lcallarec/united) - A library for unit manipulation (like kilograms, meters, etc).

## Editor Plugins

- [Vala Code](https://github.com/thiagoabreu/vala-code) - A plugin for VIsual Studio Code that enables basic autocompletion and syntax highlighting for Vala.
- [Vala-TMBundle](https://github.com/technosophos/Vala-TMBundle) - A TextMate bundle that provides Vala syntax highlighting, code completion, etc. Sublime Text 3 can also use this plugin.
- [language-vala-modern](https://atom.io/packages/language-vala-modern) - Provides Vala language support in Atom. It's a fork of the unmaintained "language-vala package".
- [Vala Syntax 4 Sublime Text](https://launchpad.net/valasyntax4sublimetext) - A basic plugin for Sublime Text 3 that provides syntax highlighting.

## Language Servers

- [vala-language-server](https://github.com/benwaffle/vala-language-server) - A language server that aims to provide code completion, formatting, syntax highlighting, and everything else according to the Language Server spec.

## Graphic Libraries

- [Cairo](https://cairographics.org/) - A 2D graphics library with support for multiple output devices. This is pretty much the default library you get in Vala.
- [SDL2](https://www.libsdl.org/) - A cross-platform development library designed to provide low level access to audio, keyboard, mouse, joystick, and graphics hardware via OpenGL, Direct3D, and Vulkan. Bindings are included in Vala and will be available starting with Vala 0.52.
- [GRX](https://github.com/ev3dev/grx) - A graphics library for simple graphics displays (think 1-bit displays or Adafruit's PiTFT displays). It also includes keyboard, mouse, joystick and touchscreen input support.
- [GEGL](http://gegl.org/) - A data flow based image processing framework, providing floating point processing and non-destructive image processing capabilities. Think of it as "Reactive Programming for Images".
- [Babl](http://gegl.org/babl/) - A dynamic, any to any, pixel format translation library.

## GUI Programming

- [GTK](https://www.gtk.org/) - The de facto library for GUI development in Vala. Bindings are included with the vala compiler.

## Multimedia Processing

- [GStreamer](http://gstreamer.freedesktop.org/) - A powerful framework for creating multimedia applications.

## XML & Data Serialization

- [GXML](https://gitlab.gnome.org/GNOME/gxml/) - A GObject API for manipulating XML and a Serializable framework from GObject to XML.
- [Json-GLib](https://gitlab.gnome.org/GNOME/json-glib/) - Implements a full JSON parser and generator using GLib and GObject, and integrates JSON with GLib data types.
- [libyaml-glib](https://github.com/rainwoodman/libyaml-glib) - The GLib binding of libyaml, plus a GObject builder that understands YAML.

## Templating

- [Compose](https://github.com/arteymix/compose) - A functional templating library for Vala.
- [template-glib](https://gitlab.gnome.org/GNOME/template-glib) - A library for template expansion which supports calling into GObject Introspection from templates.

## Numerical Computation

- [vast](https://github.com/rainwoodman/vast) - A project for generative modeling in Vala. Think of TensorFlow rewritten in Vala.
- [balistica](https://github.com/fusilero/libbalistica) - An open source ballistic simulation library. There's a complete calculator [here](https://github.com/fusilero/balistica).

## Crypto & Security

- [GnuTLS](https://www.gnutls.org/) - A secure communications library implementing the SSL, TLS and DTLS protocols and technologies around them. It provides a simple API to access the secure communications protocols as well as APIs to parse and write X.509, PKCS #12, and other required structures.

## Web Development

- [Valum](https://github.com/valum-framework/valum) - A Web micro-framework entirely written in Vala.
- [Ambition](https://github.com/AmbitionFramework/ambition) - A web framework written in Vala, with the MVC pattern in mind. Kinda unmaintained (someone could refactor it to use Valum under the hood, and maybe move it to Meson 😉)

## IoC and Dependency Injection

- [Vadi](https://github.com/nahuelwexd/Vadi) - An IoC Container developed in order to facilitate the usage of dependency injection for Vala developers.
