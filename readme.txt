# Building a Cache in Logism
A cache system that operates on LRU eviction method.
Includes an implementation of the Mealy Finite State Machine to simplify cache logic into multi-clock cycles
Utilized flip-flops, registers, and multiple sub-circuits to recreate a fully functional cache.


6 Clock Cycles Max, 7 different states 
https://docs.google.com/drawings/d/1bnYWWfpKpqh1O-J4dpB6bE29lVHKwLvLtsrH38i3CCk/edit?usp=sharing

Cache Logics
https://docs.google.com/spreadsheets/d/1hJ31U5a2D0kiOPhrdJug5HRcDcGqncqG9z8lAisLnsk/edit?usp=sharing

Details: DidContain and ByteRead are read when Ready is 1


Specifications:
CPU Address: 10bits
Cache Data Size: 24 Bytes
Number of Sets: 2
Number of Ways: 3
Block Size: 4
Write Polciy: Write Back
Eviction Policy: LRU
