# EtherFileCertification

## Summary

Upload, certify and verify a file on the Ethereum blockchain through a simple web-page.


## Context
This script was developped during an Ethereum Hackathon hosted at the Geneva University on the 26 November 2014.

## Description
A simple HTML5 and javascript page uploads any selected file locally. The Javascript is calling the local instance of Ethereum. The file is opened as a string and a Hash is generated. The Hash of the file is compared with already existing Hashes. If a similar Hash is found, the Javascript will show the timestamp of the verification. If not, the Hash of the file is sent by the contract.

## License
This work is licensed under a Creative Commons Attribution 4.0 International License available at http://creativecommons.org/licenses/by/4.0/.

## Prerequisites:

- A working webserver
- A working instance of ethereum

## Instruction to install:

1. Create the contract
Copy paste 
2. install html files on the webserver
3. Modify the index.html with the Ethereum Contract adress
