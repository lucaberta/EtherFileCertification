# EtherFileCertification

## Summary

Upload, certify and verify a file on the Ethereum blockchain through a simple web-page.


## Context
This script was developped during an Ethereum Hackathon hosted at the Geneva University on the 26 November 2014.

## Description
A simple HTML5 and javascript page uploads any selected file locally. The Javascript is calling the local instance of Ethereum. The file is opened as a string and a SHA-256 Hash is generated. The Hash of the file is compared with already existing Hashes. If a similar Hash is found, the Javascript will show the timestamp of the verification. If not, the Hash of the file is sent by the contract. Responsive design with Bootstrap.

## License
This work is licensed under a Creative Commons Attribution 4.0 International License available at http://creativecommons.org/licenses/by/4.0/.

## Prerequisites:

- A working instance of alethzero ethereum client
- (optional) a working Webserver

## Instruction to install:

1. Create the contract
Copy paste 
2. install files in the "html" folder locally or on the webserver
3. Modify the index.html with the Ethereum Contract adress

## Running the script

- Launch the alethzero client
- Paste the link of the html page in the alethzero built-in browser (either a local or an internet link)
- Upload a file

## External ressources
- Ethereum project https://github.com/ethereum/cpp-ethereum
- Bootstrap http://getbootstrap.com/
- crypto-js https://code.google.com/p/crypto-js/
