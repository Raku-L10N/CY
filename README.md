[![Actions Status](https://github.com/Raku-L10N/CY/actions/workflows/linux.yml/badge.svg)](https://github.com/Raku-L10N/CY/actions) [![Actions Status](https://github.com/Raku-L10N/CY/actions/workflows/macos.yml/badge.svg)](https://github.com/Raku-L10N/CY/actions) [![Actions Status](https://github.com/Raku-L10N/CY/actions/workflows/windows.yml/badge.svg)](https://github.com/Raku-L10N/CY/actions)

NAME
====

L10N::CY - Welsh localization of Raku

SYNOPSIS
========

    $ draig -e 'dywedyd "Helo Byd"'
    Helo Byd

```raku
# Must have RAKUDO_RAKUAST=1 environment variable set
use L10N::NL;
dywedyd "Helo Byd"
```

DESCRIPTION
===========

The `L10N::CY` distribution contains the logic to provide a Welsh localization of the Raku Programming Language. It installs a `draig` executable that will automatically activate the Welsh localization. And it allows one to use the Welsh localization in selected programs with a `use L10N::CY` statement.

REFERENCES
==========

[Creating a new programming language - Draig](https://dev.to/finanalyst/creating-a-new-programming-language-draig-503p)

AUTHORS
=======

Richard Hainsworth <rnhainsworth@gmail.com>

COPYRIGHT AND LICENSE
=====================

Copyright 2024, 2025 Raku Localization Team

This library is free software; you can redistribute it and/or modify it under the Artistic License 2.0.

