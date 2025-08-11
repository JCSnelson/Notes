1.
a) 3D graphics is usually implemented using linear algebra in order to compute the underlying math to display, move and manipulate objects within the game space. Linear Algebra requires a lot of calculations, especially for 3D graphics, these calculations however are not required to be performed in a specific order and as such they can greatly benefit from the extra parallel processing power given by the GPU as it typically has more cores than a CPU which would speed up parallel processing and therefore the graphics calculations. (2)
b)
1) Hardware requirements, different games require different types/speeds of hardware to run based on what processes the game runs. For example some games do not support parallel processing on the CPU and so a better single core performance would be more valued.
2) Compilation, games designed for other companies consoles could be compiled into machine code that is different to the machine code needed to be run on the gaming companies console, this means none of the games commands would run correctly and as compilation is not easily reversible it would be hard to get the game compiled for the different system.

2.
Utility software is a type of systems software specifically designed for helping manage and utilize hardware effectively, one example would be a disk defragmenter which helps fix fragmented Hard Drives.

3.
Magnetic - Heavier (not needed to travel anyway), less expensive, bulkier, more rewrites (installing and updating games), slower
SSD - Lighter, more expensive, less bulky, problems with rewrites, faster (access games).
For a keen video games player using a desktop PC there is many different factors that come into play when deciding between a magnetic or solid state hard drive.
Magnetic drives tend to be heavier and more bulky for a given amount of storage as well as more fragile due to the moving parts inside of them which can break under impact, this juxtaposes SSDs which are lighter and less bulky for a given amount of storage and so are more portable. However the portability may not matter as much in the context as it is a desktop PC which isn't designed to be portable or dropped anyway.
Another thing to consider is the cost for a given amount of storage, as SSDs have much more complex technology they will almost always cost more than their Magnetic drive counterparts and therefore can be a good option as many games require 100s of gigabytes of storage.
Thirdly Magnetic Drives are slower than SSDs due to their parts needing to move to access data whereas SSD's can just directly access any data, this can affect the loading time of games as the data has to be loaded into main memory, it can also affect the boot time of the pc etc.
A final point is that SSDs have a rewrite limit after which they may experience some failures while for newer SSDs this limit is high enough to not be as much of a problem it still could end up as a problem over Magnetic Drives which don't have this, specifically with updating games.
Overall weighing all the factors in I would recommend an SSD, particularly for a keen video games player as they will likely benefit greatly from the faster load times in games and that should justify the more expensive price, the rewrite limit could come into play but if they buy a newer SSD then it shouldn't affect them till way after they may consider upgrading.

4.
When the line SUB one is executed the address associated the identifier one will be loaded into the MAR (memory address register) the CU (control unit) will then send a read signal along the control bus as well as the address being sent from the MAR to the memory which will read the data at the given address and then send it along the data bus to be stored in the MDR (Memory Data Register) the contents of the MDR is then sent to the ALU via an internal bus and stored in one of the helper registers there before the ALU performs the subtraction operation using the stored value and the value stored in the accumulator before storing the result in the accumulator.

5.
Firstly there is the key differences in how they work. OOP is completely designed around objects and classes which are the blueprints to create objects whereas procedural programming works purely around procedures and functions. In OOP Functions and procedures are declared within the classes to be used upon the objects and any variables or data the objects are storing, objects can also store other object through Encapsulation whereas in procedural programming procedures and functions can be called independently of any object which is an advantage over object oriented programming as you don't need to declare a new object just to use a function. Different classes can inherit functions and traits from other ones and build upon them in different ways, this is called Inheritance and it helps support code maintenance future development as you can add new child classes and fixing the bug in the parent class will fix it for any classes that inherit it. In procedural programming functions can call other functions as part of there code but it does not provide as many ways to compartmentalize code for ease of maintenance and future development. Object oriented programming is inherently abstract allowing the operating system to be split up into its different parts as different classes and coded by different developers in parallel without having to worry about exactly how the other objects work using black box abstraction which is a clear win over procedural programming as it can be hard to fully abstract a whole other system if it is not encapsulated within a separate object. Another benefit of object oriented coding over procedural programming is Polymorphism, this allows the same function to act differently depending on the object type it is called on which can allow for greater versatility and less code needed to check if you could be dealing with multiple data types. Procedural programming is notably less complex, there is less technical knowledge needed in order to use it as opposed to object oriented programming which can often be harder to debug and understand all of the concepts required to get the benefits from it. Another downside of OOP is that if you end up with too long of an inheritance chain it can often slow your program down leading to a worse overall user experience.
Overall I would say that although OOP is more complex and can lead to slower code if used wrongly it is still a better choice for the developer team due to its features allowing for easier maintenance, future development and abstraction as well as making it easier to work together as a team.


6.
a) \<img src="UKstamps.jpg">
b)\<a href="http://ukstampcollectorsguild.co.uk">Find out more about UK stamps\</a>
c)
i) It will be harder and more typing in order to maintain a clear and consistent style throughout the website including different webpage.
ii) They will not be able to edit the sites styling easily, especially if they have conditions such as dyslexia where they may prefer specific background colours.
d) The current page needs to be changed by adding a style to the body html element to set the background colour to lightGreen e.g. \<body style="background-color:lightGreen"> which would set the default background colour of the body to lightGreen.
e) The PageRank algorithm works based on how many ranked pages reference the site, it also depends on how many pages the ranked pages have referenced as well as their rank. It would affect his ranking more if the pages where higher ranked and referenced less pages on them as their ranks get split between the pages they reference.

7.
a)
i) Paging uses static sized pages of memory and therefore if program data over runs even by a little bit it uses up a whole other page. On the other hand, segmentation uses dynamic sized memory where the size of the segment depends on the size of the program which can be harder to track.
ii) A way the operating system may overcome the problem of physical memory being full is through virtual memory. This virtual memory uses part of the secondary storage and dedicates it to storing pages or segments of memory that are not currently being used. The pages/segments will be swapped back in to the faster access main memory when they need to be used by a program. This can be hard to track as the system will need to be able to match the virtual addresses of the memory in the program code to the data needed wherever it is stored and make sure it is switched to main memory when needed.
b)
i) An interrupt is a signal within the computer, often communicated through the control bus, this signal indicates an important event to be handled or a program to be run as well as telling the computer its importance so it can be handled accordingly.
ii) When the CPU receives an interrupt it joins a queue in order to be processed. It then waits till the current FDE cycle is finished before processing the interrupts and seeing if any of them have higher importance than the current interrupt its on and then if one is more important it will transfer to running the most important one by pushing the current program data and state of registers to the top of the memory stack before loading the address of the instruction to be executed into the CIR and resuming the FDE cycles.
8.
Pipelining could help the CPU to execute the code in Fig 3.1 more quickly by freeing up use of registers and busses when they are no longer in use so that part of the next instruction can be decoded or executed while the previous instruction being fetched. In this case after the memory address register has sent the address for the indirect addressing from instruction one then the address of the next instruction can be copied to the MAR.
9.
a) 9:40
b)
def timeValue(s):
	return int(s.replace(":","").lstrip('0'))
c)
function nextBus(stopName, currentTime)
	for time in times\[stopName\]
		value = timeValue(time)
		if value > currentTime
			return time
10.
a) Their is non key dependencies in the table, firstly the branch name depends entirely on the sort code and secondly the Forename and Surname depend entirely on the CustomerID.
b) The database could be put into third normal form by removing all non-key dependencies. This would mean moving both the customer Forename and Surname to a seperate table called Customers with the CustomerID as a foreign primary key. You would also have to remove the Branch Name to a seperate table called Branches with the Sort Code as the primary key.
11.
a)
XOR: 000011100000000100010001
b)
XOR: 010011110100001101010010
c)
The encryption above is symmetric as the same key can be used for both encryption and decryption of the data. It also requires the same method.
d)
With symmetric encryption it is impossible to setup a secure line of communication as if you send out the key for someone to send an encrypted method to you then you are also sending out the key for someone to intercept and decrypt that message. With asymmetric encryption this changes as you can send out an encryption key which someone can encrypt a message with but only the person who has the corresponding decryption key will be able to decrypt the message. With the asymmetric encryption the other person can then setup a secure encrypted way of communicating with new keys so that you can send messages to them that other people cannot decrypt.
12.
a)
\#warning {
color: red,
font-family: monospace,
}
b)
The HTML line can be broken down into three parts. First the tag is an input tag which means it will be used as an input for the form. Second the type="text" this specifies it as a text box input that will display the text entered. Third the name="username" this specifies the name to be used when you need to access the data input in that field of the form.
c)
There is many differences between server and client side processing with respect to webpages.
One thing to consider with server side processing is it uses the servers resources which can lead to overall slowdown especially with higher client count as there will almost certainly be more resources per person if you utilize client side processing. Client side processing can also lead to less cost in hosting the server.
On the other hand, client side processing is less private, users can manipulate the code designed to run client side and use that to pervert the websites true purpose, for example if the login form was run client side then they could possibly use it to grab user data from the users form. Server side processing is more private and secure as the user cannot edit any of the script running, however the users inputs need to be properly sanitized to avoid things like SQL injection from being used maliciously (e.g. dropping the users table).
Server side processing also avoids stuff like sending user passwords from the database to the client which could be intercepted especially with non encrypted communication.
Server side processing is more suited to operations that need to be secure, for example user logging in or dealing with other sensitive data before communicating to the client with non sensitive data.
On the other hand Client side processing is more suited to non private but heavier processing, for example running web games. It can also be utilized to do stuff like check formatting of passwords/inputs before sending it off to the server to reduce the strain on it.

d)
The code in Fig 8.1 gets the inputted username and password from the HTML form before substituting the username into the prepared SQL statement to get the corresponding password hash to the username from the users table in the database. The password hash is then checked against the hash of the inputted password and if they match it will move to generating the success webpage and if not it will move to log the ip address that tried to log in to the database.
e)
i)
An IP address is a part of the TCP/IP system that is assigned to each computer in a network to uniquely identify it.
ii)
This will allow them to see if the same device is making multiple failed attempts to log in to an account in order to prevent someone from stealing that account.
f)
i)"SELECT passwordHash FROM users WHERE name = 'admin'"
ii)0e5a511
g)
i)"SELECT passwordHash FROM users WHERE name = 'DenverJ34';DROP TABLE users;'
ii) The first query would successfully run still returning the passwordHash, but then the second statement would run and the users table in the database would be dropped losing all the data.
iii) The Computer Misuse Act of 1990
13)
a)
D'A'+ABC+B'C'D'
b)
i)A
ii)(AVB)'
iii)AVB
14)
a) the purpose of a flip-flop is to be clock controlled single bit memory storage 
b)\_--\_\_-
15)
a)
i)it is not normalised
ii)normalised floating point numbers do not have a more than 1 zero on the left.
b)01001010 0010 = 00100101 0011
00200212
01001100 0011
00100101 0011 - 
\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_
00100111 0011

normalised
01001110 0010

16)
Multicore and multithread
Overclocking - used when you can handle heat dispersion and power but using for too long 
GPU - Parallel processing, 3D graphics, neural networks
Distributed OS - Parallel processing, using both cpu and gpu power 
SuperComputer
Quantum Computing - parallel processing, however needs different algorithms due to use of qbits finding solutions through verification.



