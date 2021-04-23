# Hyde
A simple static site generator

### Overview
Hyde is a simple static site generator which I made as a replacement for jekyll, which is too complicated for simple uses and not suitable for quick style changes.

### Layout
The names of all the folders are assumed self-explanatory; however, it is important to note that the `public` directory has no important code -- it is simply the built version of the markdown files in the `pages` directory. Most of the files in the `pages` directory are for show and for testing hyde. **The actual hyde script is located in the `_scripts` directory**

### Usage
Install all the requirements from `requirements.txt`, then run `_scripts/hyde.py --help` to get a list of the commands and it's respective help.

Note: running the script from the root directory of the repository is crucial for it to work. If this is not followed, the user will recieve errors.

### License
This code is licensed under the GNU AGPLv3 license and any later versions.

### Additional Copyright Notice
The design, styles, html, and text all belong to Aarush Gupta under copyright.
