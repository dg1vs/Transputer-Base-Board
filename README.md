# Transputer-Base-Board

This project is a 4-TRAM Transputer Base-Board. TRAMs are small subassemblies of transputers (or other components with INMOS links), a few discrete components, and sometimes some RAM and/or application specific circuitry with a standard pinout.
This base-board is a compact carrier board for up to four Transputer TRAM modules, arranged as a linear processing pipeline. The board provides the mechanical sockets, power distribution, clock generation, reset/analyse/error service wiring, and Transputer serial link routing required to operate four TRAMs as an ordered chain. The intended module order follows the pipeline ideas, that means 

PipeHead → Slot 0 → Slot 1 → Slot 2 → Slot 3 → PipeTail

The external host or upstream Transputer network connects to PipeHead, entering the first TRAM in Slot 0. 


I reused different ideas from different sources
* https://github.com/DigiFennek/TransputerBox
