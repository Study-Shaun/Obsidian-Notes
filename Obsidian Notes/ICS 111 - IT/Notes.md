## 28-Aug-23
- theoretical model of computer design -> Von Neumann architecture
	- Memory
	- Input / Output
	- CPU
	- ALU -> arithmetic & logic unit

- stored program concept -> instructions stored as binary values
	- sequential execution of instructions

- Memory -> functional unit of a computer
	- stores and retrieves instructions and data
	- binary numbering system

	- Memory Address Register (MAR) -> stores the memory address of data which will either be fetched or stored
	- Memory Data Register (MDR) -> stores a temporary copy of a data stored at location specified by MAR

- Fetch(address)
	1) load address into the MAR
	2) decode the address in the MAR
	3) copy data to the MDR
- Store(address, value)
	1) load the address into the MAR
	2) load the value into the MDR
	3) decode the address in the MAR
	4) store the contents of the MDR at the memory location

- Cache Memory
	- Von Neumann assumed that computer would get needed instructions or data directly from the RAM
	- when computer processors got faster, the speed of the RAM could not keep up
		- processors became 3000 times faster
		- memory only became 10 times faster
	- so cache memory was introduced -> memory system that temporarily stores frequently used instructions and data close to the CPU for quicker processing
		- processor first checks the cache memory for the instructions
			- if not found, accesses from RAM (slower)
	- 5 - 10 times faster than RAM
	- order of few megabytes

## 30-Aug-23
- Principal of Locality
	- when a computer uses something, it will probably use it again very soon, and it will probably use the "neighbors" of this item very soon

- Input / Output Devices
	- allow the computer to communicate with the world outside
	- information disappears when the power is turned off
	- most ad hoc and most variable components of a Von Neumann Machine

- Mass Storage Devices
	- Direct Access Storage Devices (DASDs)
		- much faster at accessing individual pieces of info
	- Sequential Access Storage Devices (SASDs)