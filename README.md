# subtitles-downloader

Download subtitles from OpenSubtitles.org

## Installation

    npm install subtitles-downloader -g

## cli usage

    Usage: subtitles-downloader [options]

    Options:

        -h, --help           output usage information
        -V, --version        output the version number
        -f, --file <path>    File path, or glob
        -l, --langs <langs>  Languages
        -m, --mix            Mix two subtitles into one

Examples

    subtitles-downloader --f movie.mkv --l spa,eng,ru --mix
    subtitles-downloader --f "movies/*.mkv" --l spa,eng


