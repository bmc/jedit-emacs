---
title: Emacs Macros for jEdit
layout: withTOC
---

## Introduction

This site, and the accompanying [GitHub repository][] contains a set of key
bindings and some BeanShell macros for the popular [jEdit][] editor. The
key bindings and macros, together, attempt to provide a better emulation of
the GNU Emacs editor than is available out of the box with jEdit. Some of
the key bindings in the shortcuts file merely bind to existing jEdit
macros; however, others bind to macros provided by this package.

## Getting the jEdit Emacs Macros

The jEdit Emacs Macros are distributed as a source bundle. There are a few
different ways to get this package of macros.

### Downloading a Tarball or Zip File

Prebuilt zip files are available from the [downloads page][].

### Cloning the Git Repository

You can also simply clone the Git repository:

        $ git clone git://github.com/bmc/jedit-emacs.git
        $ git clone http://github.com/bmc/jedit-emacs.git

## Installation

To install the macros:

1. Copy the contents of the `jedit-emacs/startup` directory to your
   `.jedit/startup` directory (typically under your home directory).
   
2. Create a `.jedit/macros/Emacs` directory.

3. Copy the Bean Shell (\*.bsh) files in `jedit-emacs` to your newly created
   `.jedit/macros/Emacs` directory.
   
4. Copy the `shortcut.properties` file to `.jedit/macros/Emacs`.

5. Fire up jEdit. It should find the Emacs macros and automatically create
   keybindings based on the contents of `shortcut.properties`.

If you want to have jEdit search an alternate location for the macros
(it'll still look in `$HOME/.jedit/startup` for the startup file), set the
`JEDIT_SETTINGS_DIR` to the alternate directory. That directory must
contain a `macros` subdirectory, and the Emacs emulation (\*.bsh) files
must be in that alternate `macros` subdirectory.

## Copyright and License

These macros are copyright &copy; 2005-2011 [Brian M. Clapper][] and are
released under a BSD license.

## Notes

**NOTICE** This emulation software is not part of, or endorsed by, the GNU
Emacs project or the Free Software Foundation, nor is it a part of, or
endorsed by, the jEdit project.

[jEdit]: http://jedit.org/
[downloads page]: http://github.com/bmc/jedit-emacs/downloads
[GitHub repository]: http://github.com/bmc/jedit-emacs
[Brian M. Clapper]: mailto:bmc@clapper.org
