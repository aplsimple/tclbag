## What's that

This repo contains a bag of Tcl/Tk things.

They can be employed independently, <em>as is</em>.

Still, they are especially welcome in [alited](https://aplsimple.github.io/en/tcl/alited) editor, as it needs them.

The below info is mostly about them used in [alited](https://aplsimple.github.io/en/tcl/alited).

## Tcl/Tk docs

<b>Q</b>: How to get a context help on a [Tcl/Tk](https://wiki.tcl-lang.org/) command while using [alited](https://aplsimple.github.io/en/tcl/alited) editor?

<b>A</b>: Just place the caret on a [Tcl/Tk](https://wiki.tcl-lang.org/) command and press F1 - and [alited](https://aplsimple.github.io/en/tcl/alited) will display a man page for this command in a browser.

To enable this feature:

  * download [Tcl/Tk docs](https://github.com/aplsimple/alited/releases/download/TclTk-docs-8.6.11/TclTk-docs-8.6.11.zip)
  * unzip it into ~/DOC
  * set up a path to it in [alited](https://aplsimple.github.io/en/tcl/alited)'s Preferences (<em>Setup/Preferences/Tools</em> tab)

## Tclkits

The [alited](https://aplsimple.github.io/en/tcl/alited) editor can be used with a fully deployed [Tcl/Tk](https://wiki.tcl-lang.org/) of any version since v8.6.6, this way:

      tclsh ~/PG/alited/src/alited.tcl

or this way:

      wish ~/PG/alited/src/alited.tcl

However, you can also use a stand-alone [tclkit](https://wiki.tcl-lang.org/page/Tclkit) instead of <em>tclsh / wish</em> (of the fully deployed [Tcl/Tk](https://wiki.tcl-lang.org/)), this way:

      tclkit ~/PG/alited/src/alited.tcl

Just download a [tclkit](https://github.com/aplsimple/tclbag/releases) corresponding to your platform and unzip it into some directory in <em>$PATH</em>.

<b>Note:</b>

   * There may be some issues while using [tclkit](https://github.com/aplsimple/tclbag/releases) with [alited](https://aplsimple.github.io/en/tcl/alited), esp. when an external package is required.

   * This information might be helpful: [Usage tclkits with alited](https://aplsimple.github.io/en/tcl/alited/index.html#tclkit)

## Download

   * [TclTk docs](https://github.com/aplsimple/alited/releases/download/TclTk-docs-8.6.11/TclTk-docs-8.6.11.zip)

   * [tclkit 8.6.12 for Linux 32 bit](https://github.com/aplsimple/alited/releases/download/tclkit-lin32-8.6.12/tclkit-lin32-8.6.12.zip)

   * [tclkit 8.6.11 for Linux 64 bit](https://github.com/aplsimple/alited/releases/download/tclkit-lin64-8.6.11/tclkit-lin64-8.6.11.zip)

   * [tclkit 8.6.12 for Windows 32 bit](https://github.com/aplsimple/alited/releases/download/tclkit-win32-8.6.12/tclkit-win32-8.6.12.zip)

   * [tclkit 8.6.12 for Windows 64 bit](https://github.com/aplsimple/alited/releases/download/tclkit-win64-8.6.12/tclkit-win64-8.6.12.zip)

## See also

   * [alited](https://aplsimple.github.io/en/tcl/alited)

   * [Usage tclkits with alited](https://aplsimple.github.io/en/tcl/alited/index.html#tclkit)