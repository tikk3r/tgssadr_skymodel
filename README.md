# tgssadr_skymodel
[![Coverage Status](https://coveralls.io/repos/github/apmechev/tgssadr_skymodel/badge.svg?branch=master)](https://coveralls.io/github/apmechev/tgssadr_skymodel?branch=master)
[![Build Status](https://travis-ci.org/apmechev/tgssadr_skymodel.svg?branch=master)](https://travis-ci.org/apmechev/tgssadr_skymodel)
Creating a BBS Skymodel from the TGSS Alternative Data Release

http://tgssadr.strw.leidenuniv.nl/doku.php#lofar_sky_model_creator

Usage: python tgss2bbs2.py [options]

Options:

-h, --help            show this help message and exit

-s SRCID, --srcID=SRCID
                        Resolveable source name [no default]

-r RADIUS, --radius=RADIUS
                        Search radius in deg [default: 5.0 deg]

-o OUTPUT, --output=OUTPUT
                        Output filename [default: tgss.skymodel]

-p, --patch           
			Write all sources as a single patch? [default: True]

-d DODEC, --dodec=DODEC
                        Deconvolve the TGSS Beam [default: True]
