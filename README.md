# CSS Less Collection

Less v1.7 is required to compile the Toolkit without errors.

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
    @RotationDeg: 5deg;
    @ScaleRatio: 1.5;
    @TransitionDuration: 0.2s;
    @TransitionEase: ease-out;


# Bower

Install Bower at the first time when you never used it before.

    $ npm install -g bower

Install via Bower

    $ bower install CSSLessCollection
