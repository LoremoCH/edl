# edl

Simple command line tool, to copy a file (first param) over scp to your own
web server to make it public accessible.

## Used Debian Packages

libnet-scp-perl
libdigest-sha-perl
libjson-perl

## Example
`host>./edl /tmp/somefile.zip
Your file is now at https://example.com/files/17577d2f1fac1c7da5380523f87cd98ccd75bedb.zip
host>`

## Configuration
This script needs a configuration in json format. You can find
an example here [edl.json.example](edl.json.example). The default
path for this file is $HOME/.config/edl.json.
