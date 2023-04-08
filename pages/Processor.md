- [[ARM processor vs others]]
- Cache (Depend upon the version of chip and arch), This is intels i7
	- L1: 32KB
	  collapsed:: true
		- Primary cache, fastest
		- Private per core
	- L2: 256KB
	  collapsed:: true
		- Secondary cache
		- Private per core
		  collapsed:: true
			- Some arch versions share these between some cores
			- Say 4 cores then
			  collapsed:: true
				- core0 and core1 shares L2
				- core2 core3 shares L2
	- L3
	  collapsed:: true
		- Shared among cores
		-
- Arch drawing (intel)
	- [[draws/2023-04-08-11-12-29.excalidraw
- Core (Depends on model)
	- It's a physical processing unit within a processor
	- Each core can execute tasks independently, allowing for  of multiple tasks at the same time.
	- [[draws/2023-04-08-11-59-36.excalidraw