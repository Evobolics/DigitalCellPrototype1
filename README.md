# Prototype Version 1

This prototype demonstrates the following:

0) That applications can communicate each other and read each other genetics.   
1) That assemblies, and the functionality they contain, can be transferred between a population of nodes.
2) That a node can recieve an assembly, convert it to a collectible assembly, and load it into memory.
3) That a node can change what functionality it has loaded based what other nodes have choosen.  

# Instructions (Windows)

1) Download all three nodes.

2) Enable the ability for applications to listen on ports 8001, 8002, and 8003.

3) Run E01D.EvoApps.P2P.Tester.exe for node 1. 

4) If you click on the first entry "http://localhost:8001/ (local)", you will notice genes A, B cand C are set to Hi.

5) Now start E01D.EvoApps.P2P.Tester.exe for node 2 and 3.  

6) Let the nodes talk to each other for around 15 seconds.  We realize 15 second is a long time, but that is the current refresh rate.

6) Now for node 1, now click on "http://localhost:8002/ "  and then back on "http://localhost:8001/ (local)".  
You will notice that for genes B and C they are now showing the word Howdy.  This is becuase these genes are configured to automatically adopt what the majority of the other cells in the population uses.  Gene A is still set to Hi becuase it is locked and is not allow to change.  

- End -
