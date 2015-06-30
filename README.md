# RailsBase16 Color Scheme for Sublime Text


This repository contains the color scheme `tmTheme` files, compatible with __TextMate__ and __Sublime Text__.

The color scheme files have been generated with [a fork](https://github.com/tompave/RailsBase16-builder) of the original Base16 Builder, which aims to provide better syntax support for the __Ruby__ programming language and for the __Ruby on Rails__ framework.  

## Installation

The easiest way to install is via [Package Control](https://packagecontrol.io/), the color schemes are available as `rails_base_16`.

Alternatively, you can clone the repo inside the `Packages` directory of your Sublime Text data directory.


## Improved syntax highlighting

* Symbols
    * Symbols and Strings use different colors.
    * the colon uses the default punctuation color, like variable qualifiers (`@`, `$`).

![symbols](https://github.com/tompave/RailsBase16-builder/raw/master/images/symbols.jpg)

* ERB
    * `<%=  %>` tags use a color more detectable in HTML files.
    * embedded ruby code has a specific background color (as seen in Railscasts and Sublime's default Cobalt color scheme).

![ERB](https://github.com/tompave/RailsBase16-builder/raw/master/images/ERB.jpg)

* Haml
    * separate colors for `%tag`, `.class` and `#id` declarations

![haml](https://github.com/tompave/RailsBase16-builder/raw/master/images/haml.jpg)

* String Interpolation
    * embedded ruby code uses appropriate source colors, not the String color.
    * embedded ruby code has a specific background color.

![strings](https://github.com/tompave/RailsBase16-builder/raw/master/images/strings.jpg)

* Operators
    * operators (`=`, `+`, `&&`, `and`, etc) use a specific color.

![operators](https://github.com/tompave/RailsBase16-builder/raw/master/images/operators.jpg)

* SCSS
    * separate colors for CSS selectors (`.`, `#`), Sass directives (`@`), and units (`px`, `em`).
    * the color used for `$variables` doesn't clash with the color used for tag selectors (`div`, `span`, etc).
    * colors for recognized CSS values.

![scss](https://github.com/tompave/RailsBase16-builder/raw/master/images/scss.jpg)

* punctuation
    * improved handling of punctuation

![punctuation](https://github.com/tompave/RailsBase16-builder/raw/master/images/punctuation.jpg)


* module declarations
    * Module declarations now use the same color of class declarations, instead of the String color.

![module_class](https://github.com/tompave/RailsBase16-builder/raw/master/images/module_class.jpg)

* block variables
    * Block variables don't have the same relevance of `@instance` variables, and they should use a different color.

![block_vars](https://github.com/tompave/RailsBase16-builder/raw/master/images/block_vars.jpg)


### Other

* comments use the italic style.
* quotation marks use the String color.
