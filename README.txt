
Noah Holt
Aubrey Morgan
Landon Bunker

------------------------
How to run:
  Make Object files
    gcc file_name -o object_file_name
    Ex
      gcc server.c -o server

  Run files
    From same machine different terminal or different machines (worked both ways when testing.
    call the object file
      ./server(mac or linux) or .\server(windows)
    client side:
      type file name (way to set up as passable as well)
    check servers directory to make sure it is recieved.

------------------------
Bits and Pieces:
  Client: connects sockets
	  gets file name to send
	  sends file

  Server: connects sockets
	  binds to client
	  waits for file
	  reports file succes or not
	  Waits again (until terminated

------------------------
Challenges Faced:
  Finding a place to start
    Instruction a little vague (just do this)
    Book kinda helped on pg 236 but only sorta
    googled and found results from resources below
    resource at end of assignment doc was helpful
  

------------------------
Resources:
	https://www.geeksforgeeks.org/c-program-for-file-transfer-using-udp/

	https://www.tutorialspoint.com/a-protocol-using-go-back-n

	https://campuscoke.blogspot.com/2015/01/go-back-n-protocol-in-c.html

	https://www.baeldung.com/cs/networking-go-back-n-protocol
