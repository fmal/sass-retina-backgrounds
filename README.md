# sass-retina-backgrounds

Simple mixins for serving high-resolution background-images for retina displays. Uses classes generated from [Modernizr](http://modernizr.com) to target browsers which don’t support media queries.

## Syntax

    @mixin retina-background-image($image, $width, $height, $extension)

## Usage

    $img-directory: '../img';

    .logo {
      @include retina-background-image('#{$img-directory}/logo', $extension: 'png');
      width: 100px;
      height: 100px;
    }
