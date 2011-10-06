# TextMate Bundle for MediaWiki

To install with Git:

    mkdir -p ~/Library/Application\ Support/TextMate/Bundles
    cd ~/Library/Application\ Support/TextMate/Bundles
    git clone https://github.com/textmate/mediawiki.tmbundle.git MediaWiki.tmbundle
    osascript -e 'tell app "TextMate" to reload bundles'


To install without Git:

    mkdir -p ~/Library/Application\ Support/TextMate/Bundles
    cd ~/Library/Application\ Support/TextMate/Bundles
    wget https://github.com/textmate/mediawiki.tmbundle/tarball/master
    tar zxf mediawiki-tmbundle*.tar.gz
    rm mediawiki-tmbundle*.tar.gz
    mv mediawiki-tmbundle* MediaWiki.tmbundle
    osascript -e 'tell app "TextMate" to reload bundles'
