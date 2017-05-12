# TheBlackProject

TheBlackProject is a HTTP Layer 7 DoS script which is an upgraded version of GoldenEye. Many bugs have been fixed since last release of GoldenEye.

TheBlackProject is a DoS python script for http. This project is under Team Ultimate Software and Technologies association limited.
For more info. please visit Teamultimate.in.

Credits :-
Manal Shaikh

## Usage

     USAGE: ./blackproject.py <url> [OPTIONS]
    
     OPTIONS:
        Flag                  Description                                               Default
        -u, --useragents   File with user-agents to use                     (default: randomly generated)
        -w, --workers      Number of concurrent workers                     (default: 50)
        -s, --sockets      Number of concurrent sockets                     (default: 30)
        -m, --method       HTTP Method to use 'get' or 'post'  or 'random'  (default: get)
        -d, --debug        Enable Debug Mode [more verbose output]          (default: False)
        -h, --help         Shows this help


## Utilities
* util/getuas.py - Fetchs user-agent lists from http://www.useragentstring.com/pages/useragentstring.php subpages (ex: ./getuas.py http://www.useragentstring.com/pages/Browserlist/) *REQUIRES BEAUTIFULSOUP4*
* res/lists/useragents - Text lists (one per line) of User-Agent strings (from http://www.useragentstring.com)

## To-do
* Change from getopt to argparse
* Change from string.format() to printf-like
* Add more useragents
* More sockets options to be added
* Packet size and quantities information to be added.
* Add more options to attack like SYN, TCP and etc. (Rather then HTTP)


## LEGAL NOTICE
THIS SOFTWARE IS PROVIDED FOR EDUCATIONAL USE ONLY! IF YOU ENGAGE IN ANY ILLEGAL ACTIVITY THE AUTHOR DOES NOT TAKE ANY RESPONSIBILITY FOR IT. BY USING THIS SOFTWARE YOU AGREE WITH THESE TERMS.
