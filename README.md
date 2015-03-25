# CSS Less Collection

Less v1.7 is required to compile the CSSLessCollection without errors.

Import this two files to work with it.

    @import 'CSSLessCollectionDefinitions';
	
Overwrite Less variables here, if you need to.

    @import 'CSSLessCollectionMixins';


## CSSLessCollectionMixins.less

Less Mixin Toolkit for generate CSS2/3 StyleSheet files.


## CSSLessCollectionDefinitions.less

Change in what you need or not ;-)

    /* Internet Explorer Fallback Polyfill Libraries */
    @MSPIE: '/JS/PIE.min.htc';
    @MSBackgroundStretch: '/JS/backgroundsize.min.htc';
    @MSBoxSizing: '/JS/boxsizing.htc';

    /* Images for High Resolution */
    @HighDpi: ~"(-webkit-min-device-pixel-ratio: 1.5), (min--moz-device-pixel-ratio: 1.5), (-o-min-device-pixel-ratio: 3/2), (min-resolution: 1.5dppx)";
    @BigPictureExtension: "_big";


    /* Colors */
    @ColorBlack: #000000;
    @ColorWhite: #FFFFFF;
    @ColorLink: blue;
    @BackgroundColor: #cccccc;


    /* Fonts Style */

    @FontStyle: normal;
    @TextTransform: none;
    @FontWeight: normal;

    @FontSize: 16;
    @LineHeight: 16;


    /* Box and etc defaults styles */

    @BoxRoundedRaduis: 5px;
    @BoxSizingType: border-box;
    @BoxShadowInsetColor: #ccc;
    @BackgroundClipType: padding-box;
    @GradientStartColor: #ccc;
    @GradientEndColor: #fff;
    @Opacity: 0.5;


## Bower

Install Bower at the first time when you never used it before.

    $ npm install -g bower

Install via Bower

    $ bower install CSSLessCollection


## License

The MIT License (MIT) Copyright (c) 2015 Milanowicz

Permission is hereby granted, free of charge, to any person obtaining
a copy of this software and associated documentation files (the
"Software"), to deal in the Software without restriction, including
without limitation the rights to use, copy, modify, merge, publish,
distribute, sublicense, and/or sell copies of the Software, and to
permit persons to whom the Software is furnished to do so, subject to
the following conditions:

The above copyright notice and this permission notice shall be
included in all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND,
EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF
MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND
NONINFRINGEMENT. IN NO EVENT SHALL THE AUTHORS OR COPYRIGHT HOLDERS BE
LIABLE FOR ANY CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER IN AN ACTION
OF CONTRACT, TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN CONNECTION
WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE SOFTWARE.