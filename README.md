# Biomemakers notes

Javi: This is not needed anymore. This is a dependency used by phpdom, the pdf generator of Portal. This was just a fork of the original library to add a temporal patch to support php 7.2. But this problem has been fixed by the library creators.
[Our issue](https://github.com/BiomeMakers/Portal/issues/27)



# SVG file parsing / rendering library

[![Build Status](https://travis-ci.org/PhenX/php-svg-lib.svg?branch=master)](https://travis-ci.org/PhenX/php-svg-lib)
[![Coverage Status](https://coveralls.io/repos/PhenX/php-svg-lib/badge.svg)](https://coveralls.io/r/PhenX/php-svg-lib)


[![Latest Stable Version](https://poser.pugx.org/phenx/php-svg-lib/v/stable)](https://packagist.org/packages/phenx/php-svg-lib) 
[![Total Downloads](https://poser.pugx.org/phenx/php-svg-lib/downloads)](https://packagist.org/packages/phenx/php-svg-lib) 
[![Latest Unstable Version](https://poser.pugx.org/phenx/php-svg-lib/v/unstable)](https://packagist.org/packages/phenx/php-svg-lib) 
[![License](https://poser.pugx.org/phenx/php-svg-lib/license)](https://packagist.org/packages/phenx/php-svg-lib)

The main purpose of this lib is to rasterize SVG to a surface which can be an image or a PDF for example, through a `\Svg\Surface` PHP interface.

This project was initialized by the need to render SVG documents inside PDF files for the [DomPdf](http://dompdf.github.io) project.
