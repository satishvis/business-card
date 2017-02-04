Business Card
=============

Example:

<div>
    <img src="images/front.png" alt-="front side business card" max-width="350px;"/>
    <img src="images/back.png" alt-="back side business card"  max-width="350px;"/>
</div>

Requirements
------------

* Recent TeX installation (tested on a 2017 one)
* XeLaTeX
* [Font Awesome](https://github.com/xdanaux/fontawesome-latex)
* [Fira Sans](https://github.com/mozilla/Fira)

Building Documents
------------------

Build the front and back sides with XeLaTeX:

```shell
xelatex src/front.tex
xelatex src/back.tex
```

License
-------

GNU GPLv3. See LICENSE file.

© 2017 Olivier Pieters
