- Basic
  collapsed:: true
	- Typical go file format
	  collapsed:: true
		- ```golang
		  package main // The package clause
		  import "fmt" //Import section
		  
		  // The code part
		  func main() {
		  	fmt.Println("valak")
		  }
		  ```
	- Statically typed lang
	- Export a func or var
	  collapsed:: true
		- First letter of word Capital -> var Test int = 5
	- Type
	  collapsed:: true
		- ```golang
		  int, string, float, bool
		  ```
		- Type conversion
		  collapsed:: true
			- float64(myint)
- Debugger
  collapsed:: true
	- dlv
- Runtime
	- Uses both multithreading to achieve concurrency
	- For a program
	  collapsed:: true
		- It has a good scheduler for scheduling it to cores and threads
		- Creates one OS process
		  collapsed:: true
			- Contains 1 or more threads
			  collapsed:: true
				- These multiple threads can be scheduled on available cores by the OS
				- Within each thread Go Runtime can create multiple goroutines
				  collapsed:: true
					- goroutines can run simultaneously within the thread
					- they communicate using channels
			-