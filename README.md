# inform-mode

*An Emacs major mode for editing Inform 6 source code.*

## License

inform-mode is free software. You can redistribute it and/or modify it under
the terms of the GNU General Public License as published by the Free
Software Foundation, either version 3 of the License, or (at your option)
any later version.

This program is distributed in the hope that it will be useful, but
WITHOUT ANY WARRANTY; without even the implied warranty of
MERCHANTABILITY or FITNESS FOR A PARTICULAR PURPOSE. See the GNU
General Public License for more details.

See [COPYING](https://github.com/rrthomas/inform-mode/blob/master/COPYING)
for the full license.


## Introduction

inform-mode supports the usual program mode functions: automatic
indentation, moving over expressions, comment and string filling, font
locking, tags file support, starting compiles and parsing errors. You
can also run a Z-code interpreter on the compiled code.

It should work on any recent GNU Emacs.

See the [news page](https://rrthomas.github.io/inform-mode/news.html) for
details of recent changes.


## Installing inform-mode

The two easiest ways to install inform-mode are using Emacs’s package
system, from the MELPA repository, or, on Debian, Ubuntu and related
systems, using your OS’s packaging system.


### Via MELPA

[MELPA](https://melpa.org/) is a packaging system for Emacs.
Follow the instructions on the website to add MELPA to your list of
package sources. Then inside Emacs run

    M-x package-install RET inform-mode RET


### Debian, Ubuntu etc.

On Debian, Ubuntu or other derivatives you can run:

    apt-get install inform-mode

However, this may not provide the latest version: if you want this,
download the latest version from https://github.com/rrthomas/inform-mode/
and try one of the following two methods.


## Using inform-mode

After installation, inform-mode will be activated for any files ending in
`.inf` (and optionally `.h`) when you visit them using Emacs. Type `C-h m`
to view the documentation for the mode. Variables governing inform-mode can
be customized; type `M-x customize` and navigate to `Programming / Languages
/ inform-mode`.


## Latest version

inform-mode can be installed with Emacs’s built-in packaging system from
[MELPA](https://www.melpa.org/)

An older version is available from
http://ifarchive.org/indexes/if-archive/programming/editors/


## Bug reports and development

Any bugs reports, patches, feature suggestions or other feedback would be
welcomed. Please file an issue on the [GitHub
page](https://github.com/rrthomas/inform-mode)

Releases and the current development sources can also be found there. The
`master` branch tracks the released version; `testing` contains the latest
development version but may not be stable.


## Authors

Reuben Thomas is the current maintainer of inform-mode. inform-mode was
originally written by Gareth Rees. See
[AUTHORS](https://github.com/rrthomas/inform-mode/blob/master/AUTHORS) for
full details of contributors and past maintainers.
