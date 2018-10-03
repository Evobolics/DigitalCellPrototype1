# Prototype Version 1

This prototype demonstrates the following:

0) That cells can 
1) That assemblies and the functionality they contain can be transferred between nodes
2) That a node can recieve an assembly, convert it to a collectible assembly, and load it into memory.
3) That the a node can change what functionality it has loaded based what other nodes have choosen.  

# Instructions

1) Download all three nodes.

2) Enable the ability for applications to listen on ports 8001, 8002, and 8003.

3) Run E01D.EvoApps.P2P.Tester.exe for node 1. 

4) If you click on the first entry "http://localhost:8001/ (local)", you will notice genes A, B cand C are set to Hi.

5) Now start E01D.EvoApps.P2P.Tester.exe for node 2 and 3.  

6) Let the nodes talk to each other for around 15 seconds. 

6) Now for node 1, now click on "http://localhost:8002/ "  and then back on "http://localhost:8001/ (local)".  now to choose to change its gene frequencies for two of its genes and show Howdy for those genes.  
  The first gene is configured to not evolve it and will not change.
