# Information Notation
#Programming 

## Basic principles
+ bit - a bit from a digit (1 or 0)
+ easy to represent information as bits, as there are only 2 possible values
+ encoding types:
	1. unsigned: >= 0, use [[Unsigned encoding]]
	2. signed: > < = 0 [[Two's complement encoding]]
	3. floating-point: real numbers, [[Floating point encoding]]
+ limitations on bit-number representation lead to [[Overflows]] or [[Underflows]]
+ floats are imprecise, because are more infinite (1 vs 1.0002312....), and handle arithmetic differently 
+ converting between signed and unsigned doesn't change the bits, but the way they are interpreted

## Information storage
+ **byte** - 8 [[Information Notation#Basic principles|bits]], that are the [[Atomi si molecule|atoms]] of memory; an array of bytes represent the **memory**, the same way a bunch of [[Atomi si molecule|atoms make up an element]]; since it contains 8 bits, the range of it is from 00000000 to 11111111, or 0 to 255; thus, enter [[Hexadecimal Notation]]
+ every byte in the array has an **address**; all addresses in an array of bytes represent the **address space**/addresses to [[DRAM]] and other hardware storage (disks, flash)
+ memory space is split to store **[[Program Objects]]**

## Data sizes
+ word size - size of a pointer's type
+ 32 and 64-bit systems means that programs have access to $2^32-1$(4 GB) and $2^64-1$(a lot more than 4GB) bytes
+ because instructions are encoded differently on different operating systems, even those using identical hardware, binary executables are not portable