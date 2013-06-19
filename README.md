## Project Vendo

## Machine info

Machine produced by http://www.sandenvendo.it/

## Model information

* Model SVE GSP

Some photos here:

http://www.flickr.com/photos/marcusramberg/sets/72157634192791245/

## Protocol information

The machine generates reporting through the DEX protcol, and talks to modules through MDB. There are specifications for these protocols in the Manuals/ directory. Here's some info from wikipedia about MDB

http://en.wikipedia.org/wiki/Multidrop_bus

   MDB in Vending Machines 

The MDB protocol is used in vending machines to interconnect different modules (such as bill acceptors, card readers and coin changers) with one bus. The physical connection is realized as an unmodulated serial bus with a fixed data rate of 9600 baud, and 9 bits in each data word transmitted.
MDB has evolved as a standard protocol after 1995, allowing alternative (e.g. Smartcard based) payment systems to be connected to existing vending machines.
Bus addressing is based on the device type, which allows for a very simple protocol stack as no initial enumeration needs to be performed, but has the disadvantage that only one device of each type can be attached.
ccTalk [edit]
Main article: ccTalk
The ccTalk multidrop bus protocol uses an 8 bit TTL-level asynchronous serial protocol, it uses address randomization to allow multiple similar devices on the bus (after randomisation the devices can be distinguished by their serial number). ccTalk was developed by CoinControls but is used by several other vendors too.


I also find this tutorial enlightening:  http://www.vendingmarketwatch.com/article/10272928/dex-and-mdb-a-primer-for-vendors



