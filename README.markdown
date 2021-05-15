# [Hyde](https://pypi.org/project/hyde-generator/)
A simple static site generator

On version: `v0.0.2`

### Overview
Hyde is a simple static site generator which I made as a replacement for jekyll, which is too complicated for simple uses and not suitable for quick style changes.

### Layout
The names of all the folders are assumed self-explanatory; however, it is important to note that the `public` directory has no important code -- it is simply the built version of the markdown files in the `pages` directory. Most of the files in the `pages` directory are for show and for testing hyde. **The actual hyde script is located in the `_scripts` directory**

### Usage
#### If this is the first time running Hyde on your computer
Install the library with `pip3 install hyde-generator`. The PyPI page is [here](https://pypi.org/project/hyde-generator/)

#### Continued from last steps or already installed Hyde
Run `hyde build` in the `tests/` directory and then run `hyde serve` to see the built files.

### License
This code is licensed under the GNU AGPLv3 license and any later versions.

### Additional Copyright Notice
The design, styles, html, and text all belong to Aarush Gupta under copyright.
