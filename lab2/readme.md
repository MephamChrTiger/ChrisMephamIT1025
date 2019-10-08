### Executive Summary
	Here in lab 2 I've explained hard drives vs SSDs and each of their positives and negatives. I went on to explain RAM as well as CPU, logic gates, and IEEE - Ethically Aligned Designs.


### Hardware
#### Hard drives and memory;
	
	Hard drive latency is a mechanical latency measured in milliseconds and is used when talking about seek times and disk rotation. When talking about seek times, it is referring to the read/write speed of data on the hard drive disk. Latency itself is the average time for the sector being accessed to rotate into position under a head after a completed seek. Access time is the time interval between a request from the user on the system, and the time the data is available from the drive. The lower the latency on a hard drive the more performance there is, as an example hard drives as early as late 2001 had an average latency of less than 3ms. Now switching to actual transfer rates of a hard drive, usually called media rate, is the speed at which data is transferred to and from the actual platter on the disk (usually measured in MBps, or megabytes per second). Modern day hard drives have an increasing transfer rate on different diameters on the disk. Going back to disks in late 2001, an average seek time was between 4 and 7ms and max transfer rates were around 50-60MBps (again, the faster the transfer rate, the more performance the drive has). 
	
	Hard drives have been reliable and faithful for years, but with magnetic surfaces, spindles, and a vast array of moving parts, they are fallible (not to mention slow) and can break and deteriorate after years of constant use. Newer solid state drive technology has zero moving parts; no spinning platters, nothing, and its data can be accessed instantly using system-wide addresses. If this sounds familiar that's because it's been used before, this is the same technology that is used in RAM (or random accessed memory) but in the past has been to expensive to create a high-volume drive with. Compared to hard drives, solid state drives have much more performance, mostly because as stated above, hard drives has moving spinning platters, meanwhile SSD's have no moving parts and therefore has no latency when data is transfered. Another positive feature of not having any moving parts is that there is nothing to go wrong mechanically, but all this performance and reliability comes at a price. Years ago a 1tb sata SSD cost upwards of $300 while today 1tb NVME drives, with much faster read/write times and a smaller form factor, can be had for just above $100. If you're looking for capacity however, large hard drives up to 12tb do cost about $2-300 but when compared to SSDs of the same storage amount, HDDs are much cheaper (but at a performance cost). 

	RAM, or random access memory, is a high speed volatile memory that your computer uses, where all the info needed to keep your computer or system up and running is stored. Compared to hard drives with read/write speeds of about 150MBps, the average speed of your ram would be about 8000MBps, and as you can see speed is key. Let's not forget the storage space on your RAM either, where most computers these days come with 4-8gb for normal use (internet browsing and even playing games never use more than 8gb of RAM). What happend if we add more? As an example, if you have 2gb of RAM on a laptop and let's say it takes about 1.5gb to run windows 10, and 500 megabytes or more (1024megabytes equals 1gb) goes to opening chrome, your system is using all 2gb of your RAM, and therefore you will have no room for anything else and your system might run slow. If we increase the amount of RAM in your system to 16gb, then you could have chrome open, be playing a game, and doing other things, and still have some RAM to spare. A good comparison would be RAM is like a train, adding more ram adds a train car to the train and allows more people (people are programs on your computer) to board the train (lets you multitask with more and more programs without slowing down). 
	
#### Hardware: ALU and the Control Unit 
	
	The control unit is like a captain in the army, and recieves its commands from RAM. Under the command of the control unit is the ALU (or Arithmetic Logic Unit) and has 2 inputs A and B. The ALU outputs to the register inside the CPU and is much faster for storing numbers while an operation is being completed. The control unit saves this number on the register and can also output those numbers through wires called the BUS, and then will clean up the BUS and surrounding registers. 
	
#### Hardware: CPU input and output 
	There are multiple ways to input into a system, where it convert physical inputs to binary information. These inputs are things such as mice, keyboards, buttons, microphones, and cameras. The memory of the computer is where all the information is stored, and the CPU (central processing unit) is where all the calculations are made. After we recieve an input and a calculation is made, there needs to be an output. An output converts information to physical output with things such as a monitor, headset, robot, phone, etc. 

#### Hardware: Logic Gates and Circuits
	A truth table is a mathematical table used in logic, specifically with booleans (true and false, 1 and 0) and lists all possible values the function can attain. A NAND gate (sometimes called a Negated AND gate) is a digital gate with two or more inputs and one output with opposite behavior of an AND gate. The NAND gate is true when one or more of an input is false. If all of the NAND gate's inputs are true then the output is false. 

#### Hardware: IEEE - Ethically Aligned Design
	IEEE is an association dedicated to advancing innovation and tech excellence for the benefit of humanity and is the world's largest professional society. IEEE (or Eye-triple-E) stands for the Institute of Electrical and Electronics Engineers. Design ethics concerns moral behavior and choices in designing anything. It guides how clients and end users of products interract with designers, like how to determine features or a product or how to assess the ethical and moral value of a product. This is important because it is the means of how scientific knowledge and technological possibilities are made into physical form and serve the desires of each person in each community. 

#### Data Representation: Numeric Conversions
	When I used to count as a kid I would use my 10 fingers to count, and if I passed 10 I would use 1 finger to signify ten while I kept counting with the others. This is called base-ten, or the decimal number system that most people use to count. Unfortunatley computers can't understand base-ten so they use binary, or base-two which is made up of 0's and 1's. Hexadecimal is completely different from binary and decimal, and usees a base-sixteen system, which means there are sixteen different digits that can be in a single place. 








