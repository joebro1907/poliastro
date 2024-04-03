**THE ORIGINAL POLIASTRO LIBRARY WAS ARCHIVED. This is a fork of it with minor modifications**

> _The original poliastro is archived and will not be developed any further, see https://github.com/poliastro/poliastro/issues/1640 for more context._
> _Forks (like this one) are welcome, please respect the license by retaining attribution, and consider rebranding your fork if you intend to develop it in the long run._
> _If you still use poliastro in your work, see below how to cite it._
> _For a more complete background of the project, see https://conference.scipy.org/proceedings/scipy2022/juanluis_cano_poliastro.html._
> Per Python ad astra!

[![poliastro Logo](https://raw.githubusercontent.com/poliastro/poliastro/main/docs/source/_static/logo_readme.png)](https://docs.poliastro.space/en/stable/)

| **Name**  |                        **Website**                         |                                                         **Authors**                                                       |                     **Version**                      |
|:---------:|:----------------------------------------------------------:|:-------------------------------------------------------------------------------------------------------------------------:|:----------------------------------------------------:|
| poliastro | [https://www.poliastro.space](https://www.poliastro.space) | [Juan Luis Cano Rodriguez](https://orcid.org/0000-0002-2187-161X) [Jorge Martinez](https://orcid.org/0000-0001-9622-2369) | [0.18.dev0](https://github.com/poliastro/poliastro/) |

poliastro is an open source ([MIT](#License)) pure Python library for interactive
Astrodynamics and Orbital Mechanics, with a focus on ease of use, speed, and
quick visualization. It provides a simple and intuitive API, and handles
physical quantities with units.

Some features include orbit propagation, solution of the Lambert\'s problem,
conversion between position and velocity vectors and classical orbital elements
and orbit plotting, among others.  It focuses on interplanetary applications,
but can also be used to analyze artificial satellites in Low-Earth Orbit (LEO).

If you use poliastro on your project, please use the DOI to cite
poliastro in your publications:

    Juan Luis Cano Rodríguez, Jorge Martinez, et al.. (2023). poliastro: poliastro 0.17.0. Zenodo. 10.5281/zenodo.6817189

![Multiple examples image](https://github.com/poliastro/poliastro/raw/main/docs/source/_static/examples.png)


## Requirements

poliastro requires the following Python packages:

- [numpy](https://numpy.org/) for basic numerical routines
- [astropy](https://www.astropy.org/) for physical units and time handling
- [numba](https://numba.pydata.org/) for accelerating the code
- [jplephem](https://github.com/brandon-rhodes/python-jplephem) for the planetary ephemerides using SPICE kernels
- [matplotlib](https://matplotlib.org/) for orbit plotting
- [plotly](https://plotly.com/) for 2D and 3D interactive orbit plotting
- [scipy](https://scipy.org/) for root finding and numerical propagation

poliastro is supported on Linux, macOS and Windows on Python 3.8 to 3.11.


## Installation (this fork)

``python -m pip install https://github.com/joebro1907/poliastro/archive/main.zip``

## Documentation

Complete documentation, including a [quickstart guide] and an [API reference], can
be read on the wonderful [Read the Docs]. Multi-version documentation includes:

* [Development documentation](https://docs.poliastro.space/en/latest/)
* [Stable documentation](https://docs.poliastro.space/en/stable/)


## License

poliastro is released under the MIT license, hence allowing commercial use of
the library. Please refer to the [COPYING] file.

    The MIT License (MIT)
    
    Copyright (c) 2012-2023 Juan Luis Cano Rodríguez, Jorge Martínez Garrido, and the poliastro development team
    
    Permission is hereby granted, free of charge, to any person obtaining a copy
    of this software and associated documentation files (the "Software"), to deal
    in the Software without restriction, including without limitation the rights
    to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
    copies of the Software, and to permit persons to whom the Software is
    furnished to do so, subject to the following conditions:
    
    The above copyright notice and this permission notice shall be included in all
    copies or substantial portions of the Software.
    
    THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
    IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
    FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
    AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
    LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
    OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
    SOFTWARE.


## Problems and suggestions

If for any reason you get an unexpected error message or an incorrect result,
or you want to let me know about your use case, please open a new
issue in the [issue tracker].

I'm a begginer in Python, so I'll try my best, but that's what github is for: collaboration and improvement :)

## Frequently asked questions

* **What's up with the name?**

  poliastro comes from Polimi, which is the shortened name of the Politecnico di
  Milano, see the [acknowledgement from the original author]. *Grazie mille!*

* **What's the future of the project?**

  The **original** poliastro repository has been archived. This is just a fork with some minor modifications to make my IOD project work. See #link here

<!-- LINKS AND REFERENCES -->

[quickstart guide]: https://docs.poliastro.space/en/stable/quickstart.html
[API reference]: https://docs.poliastro.space/en/latest/api.html
[Read the docs]: https://readthedocs.org
[binder]: https://mybinder.org/
[alternative installation methods]: https://docs.poliastro.space/en/stable/installation.html#alternative-installation-methods
[issue tracker]: https://github.com/poliastro/poliastro/issues 
[CONTRIBUTING.md]: https://github.com/poliastro/poliastro/blob/main/CONTRIBUTING.md
[COPYING]: https://github.com/poliastro/poliastro/blob/main/COPYING
[mailing list]: https://groups.io/g/poliastro-dev
[chat room]: http://chat.poliastro.space/
[let us know]: mailto:hello@juanlu.space
[examples directory]: https://github.com/poliastro/poliastro/tree/main/docs/source/examples
[docs_stable]: https://docs.poliastro.space/en/stable/
[docs_latest]: https://docs.poliastro.space/en/latest/
[commonly used Astrodynamics software]: https://docs.poliastro.space/en/stable/related.html
[open an issue]: https://github.com/poliastro/validation/issues/new
[milestones]: https://github.com/poliastro/poliastro/milestones
[Want to be a backer]: https://opencollective.com/poliastro#backer
[gallery of examples]: https://docs.poliastro.space/en/latest/gallery.html
[becoming a backer]: https://opencollective.com/poliastro#backer
[becoming a sponsor]: https://opencollective.com/poliastro#sponsor
[acknowledgement from the original author]: https://docs.poliastro.space/en/stable/history.html#acknowledgement-from-the-original-author

<!-- Badges -->

[poliastro_badge]: https://img.shields.io/badge/poliastro-gray.svg?logo=data:image/png;base64,iVBORw0KGgoAAAANSUhEUgAAABAAAAAQCAYAAAAf8/9hAAAABHNCSVQICAgIfAhkiAAAAbxJREFUOE+Vk79LAmEYx7/njzulHKLQQIKwiyLuohykxqJBaHMNwvorcmltbG6LhnBqrMiWlmYl0SydaoqgwbLz9DS/B++heUI98A73vs/zfZ7n8zwndXsGF6tUKojFYvD7/W7Pzp00SiCXyyGTySCZTCKVSiEej7sKjRSgdzqdRq1WQzabRTQa/b8Ag8vlMsLhMBKJxN8F2u02LMtyAur1OqqFe+jaEsYi6oDQUAuGYcDn89nHsR7nq+N9zKxsQdvcGS3QbDYhyzJYQafTGSzZMvBQeoau61AUZXgKLJkTZaDX64XH40Gr1bIdKWqaJorFIjRNs995aE4LIjsdOXsGK9YT0HqHoawjEAggf3OJ2eUVBCcmnSoGBEQ2BsteA6juAY08unNn+HgN4fboEItqDAsHR6MF2B+rkMnwcRtov6E7fwGzM42781PEdQ2h1TV3AZInB6nX/8l1AbsbixhXJBgmUCqV7GWKRCJguwKk0wLhESQnEAwGcVd8wZTnE9+NLxuoqqo2B0mSHMgDEPnB0kmXDPp3gfesjHCZgFMRNrRIdKYxq9hGESgg9y+I68/EdsQOCGeKUPS3/QDL/fnRmszmsAAAAABJRU5ErkJggg== "poliastro"
