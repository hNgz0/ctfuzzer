## ctfuzzer - fast local dns fuzzer

![sheilong](https://i.imgur.com/ximZs7d.png)

## How it works

shape and makes use of /etc/hosts as local dns, for discovery of subdomains through brute force

## Installation

git clone https://github.com/hNgz0/ctfuzzer/

chmod 755 ./ctfuzzer/ctfuzzer

mv -v ./ctfuzzer/ctfuzzer /sbin/ctfuzzer && rm -f ./ctfuzzer

## Dependencies
ffuf - https://github.com/ffuf/ffuf

curl - https://github.com/curl/curl
