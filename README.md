
# DifferentiationDetector

This software is covered by the CRAPL licence (see CRAPL-LICENSE.txt)

## Usage

  Include arguments in configs_local.cfg or pass through the command line.

### Replay Analyzer Server
  Requires TShark 1.8+ and Tornado(http://www.tornadoweb.org/)
  
  $ sudo python replay_analyzerServer.py --ConfigFile=configs_local.cfg
  
  
### Replay Server
  Paths to Pcap pickles need to be given in a file.
  
  $ sudo python replay_server.py --ConfigFile=configs_local.cfg
 
