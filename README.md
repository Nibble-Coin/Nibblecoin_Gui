# Nibblecoin_Gui

## How to compile Nibblecoin GUI wallet

## Download dependencies

> sudo apt-get install build-essential git cmake libboost1.55-all-dev

> sudo apt-get install qt5-default

If libboost doesnt download with this command do this command:

> sudo apt-get install libboost-all-dev

## Download the source code

> git clone https://github.com/Nibble-Coin/Nibblecoin_Gui

If you don't have git installed, run this command:

> sudo apt-get install git

## Make a build folder

> mkdir build

> cd build

## Make the makefiles

> cmake [Nibblecoin_Gui path location]

You can find the path location by dragging Nibblecoin_GUI folder into the terminal

## Compile the source

> make

## Load the wallet

Load the GUI wallet and it should begin to sync with the blockchain, once it is done syncing you are ready to start sending and
recieving Nibblecoin!
