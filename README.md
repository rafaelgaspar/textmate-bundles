Textmate Bundle Pack
====================

To install all the bundles:

    cd ~/Library/Application Support/TextMate
    git clone https://github.com/rafaelgaspar/textmate-bundles.git Bundles
    cd Bundles
    git submodule init && git submodule update
    osascript -e 'tell app "TextMate" to reload bundles'