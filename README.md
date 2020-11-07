# ngpique
An idea collection for a new Ace of Spades server infrastructure


Objectives:
* Server should run faster
* Core modules should be more easily accessible
* Better memory security
* Easier debugging for scripts
* Scripts and maps should be exchangeable and reloadable while the server is already running
* It should not be too difficult to change from the Python architecture 


Possible solutions:
* Using Rust as main language
* Scripts should not run in chain, instead after another with communicating to the core
* Constantly called functions should run in separate threads
* (Maybe) using a modified version of pyrs to transpile Python3 scripts to the Rust architecture or using RustPython to interpret Python3 code with Rust


Disclaimer: These are just ideas and maybe they are not even good. 
Feel free to comment!
