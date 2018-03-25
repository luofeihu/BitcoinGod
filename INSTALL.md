## Installation

It is the Bitcoin God client and it builds the backbone of the network. It downloads and, by default, stores the entire history of Bitcoin transactions (which is currently more than 150 GBs); depending on the speed of your computer and network connection, the synchronization process can take anywhere from a few hours to a day or more.

. Before running, it's recommended you create an RPC configuration file,create an RPC configuration file on OSX




You can monitor the download process by looking at the debug.log file:
	

	bitcoingod-cli --help # Outputs a list of command-line options.
	bitcoingod-cli help # Outputs a list of RPC commands when the daemon is running.
	
See more [RPC commands List](https://github.com/BitcoinGod/BitcoinGod/blob/master/doc/RPC_LIST.md).