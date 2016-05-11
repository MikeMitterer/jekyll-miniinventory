GitHub
    http://mikemitterer.github.io/jekyll-miniinventory/

Config
    jekyll serve --config _config.yml,_config_dev.yml

Search:
    https://github.com/slashdotdash/jekyll-lunr-js-search

Cheat-Sheet
    http://news.humancoders.com/t/developpement/items/11149-jekyll-cheat-sheet

Thumbnails
    http://cubiq.org/create-fixed-size-thumbnails-with-imagemagick
    mogrify -resize 100x100 -background white -gravity center -extent 100x100 -format png -path thumbs *.*
    mogrify -path thumbs -format png -resize "100x100^" -gravity center -crop 100x100+0+0 +repage *.jpg

    mogrify -path images/thumbs -format png -resize "100x100" -gravity center -extent 100x100 -background white images/*.*
