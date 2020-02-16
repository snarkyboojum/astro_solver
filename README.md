## Overview

This library provides a simple and fast software astrometric solver, implemented in Rust.

The Gaia Catalogue is used for as an up to date, comprehensive and accurate astrometric reference catalogue. The model returned is based on the World Coordinate System (WCS), which is a simple linear model. Eventually a more sophisticated method, perhaps based on Simple Imaging Polynomial (SIP) might be implemented.

## Objectives

The three primary goals for this library are correctness/accuracy, speed and small footprint (in terms of memory and computing requirements).

Eventually the library might be embeddable, and so having minimal runtime requirements is also of interest. It might make sense to run this natively on a microprocessor for calibration of telescope mounts for example - speed and accuracy could be important for auto-guiding requirements.

## Further information

- [Astrometic solving](https://en.wikipedia.org/wiki/Astrometric_solving) on Wikipedia
- [Gaia Data Release 2](https://gea.esac.esa.int/archive/documentation/GDR2/) from the ESA
- [Gaia Data](https://gea.esac.esa.int/archive/) from the Gaia Archive
- [FITS World Coordinate System (WCS)](https://fits.gsfc.nasa.gov/fits_wcs.html)