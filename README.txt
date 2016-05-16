GitHub
    http://mikemitterer.github.io/jekyll-miniinventory/

Config
    jekyll serve --config _config.yml,_config_dev.yml
    jekyll _3.0.5_ --config _config.yml,_config_dev.yml serve

Search:
    https://github.com/slashdotdash/jekyll-lunr-js-search

Tips
    http://jekyll.tips/

Dart
    https://dartpad.dartlang.org/9126d5d48ebabf5bf547

Cheat-Sheet
    http://news.humancoders.com/t/developpement/items/11149-jekyll-cheat-sheet
    https://github.com/Shopify/liquid/wiki/Liquid-for-Designers

Thumbnails
    http://cubiq.org/create-fixed-size-thumbnails-with-imagemagick
    mogrify -resize 100x100 -background white -gravity center -extent 100x100 -format png -path thumbs *.*
    mogrify -path thumbs -format png -resize "100x100^" -gravity center -crop 100x100+0+0 +repage *.jpg

    mogrify -path images/thumbs -format png -resize "100x100" -gravity center -extent 100x100 -background white images/*.*
