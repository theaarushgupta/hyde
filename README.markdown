# Hyde
A simple static site generator

### Overview
Hyde is a simple static site generator which I made as a replacement for jekyll, which is too complicated for simple uses and not suitable for quick style changes. However, I still belive jekyll is a better choice for blogs and things where many different pages -- or posts -- are needed to be converted from markdown to html.

### Layout
The names of all the folders are assumed self-explanatory; however, it is important to note that the `public` directory has no important code -- it is simply the built version of the markdown files in the `pages` directory. Most of the files in the `pages` directory are for show and for testing hyde. **The actual hyde script is located in the `_scripts` directory**

### Usage
Install requirements from `requirements.txt`, initialize the virtual environment, then run `_scripts/hyde.py --help` to get a list of the commands and it's respective help.

### License
This code is licensed under the GNU AGPLv3 license and any later versions. Please contact Aarush Gupta for any doubts concerning the license.

### Additional Copyright Notice
The design, styles, html, and text all belong to Aarush Gupta under another copyright. See [this repository](https://github.com/theaarushgupta/theaarushgupta.github.io) for more information regarding that.