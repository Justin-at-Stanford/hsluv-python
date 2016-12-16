[![Build Status](https://travis-ci.org/hsluv/hsluv-python.svg?branch=master)](http://travis-ci.org/hsluv/hsluv-python)
[![Package Version](https://img.shields.io/pypi/v/hsluv.svg)](https://pypi.python.org/pypi/hsluv/)

A Python implementation of [HSLuv](http://www.hsluv.org) (revision 3).

## Installation

`pip install hsluv`

## Usage

**hsluv_to_hex([hue, saturation, lightness])**

`hue` is a float between 0 and 360, `saturation` and `lightness` are floats between 0 and 100. This 
function returns the resulting color as a hex string.

**hsluv_to_rgb([hue, saturation, lightness])**

Like above, but returns a list of 3 floats between 0 and 1, for each RGB channel.

**hex_to_hsluv(hex)**

Takes a hex string and returns the HSLuv color as a list of floats as defined above.

**rgb_to_hsluv([red, green, blue])**

Like above, but `red`, `green` and `blue` are passed as floats between 0 and 1.

For HPLuv (the pastel variant), use `hpluv_to_hex`, `hpluv_to_rgb`, `hex_to_hpluv` and `rgb_to_hpluv`.

## Testing

Run `python setup.py test`.

## Authors

* Robert McGinley ([mcginleyr1](http://github.com/mcginleyr1))
* Alexei Boronine ([boronine](http://github.com/boronine))

