Fernando W.K.M.A
E/13/101
Lab 09
READ ME file


(1) First , open terminal in folder that has server.java file and run that file. 
	javac Server.java
	java Server
(2) Then , open new terminal in that same folder and connect to the server by using folwing commands.
	In Ubuntu     - nc loclhost 2000
	In Windows - telnet localhost 2000
that ‘2000’ means , the port where client connect to the server

(3) Then , in client terminal display like “Do you want add item(Y/N)” 
	(1)Then , you don’t want add item , then type “N”,
 	(2)Then ,  display “place your bids” on client terminal
	(3)Then ,  type your name , symbol name that you want bid 		and amount that you want  bid
	(4)Do you want bis more then type symbol name and then   		price
	(5)if you are finishing  your bid then type “quit ” to disconnect  from server.
	(6) Then you can see a table that details of some selected items after bid.

(4)  
	(1) Do you want add item , then type “Y”
	(2) Then , display “Enter your symbol name of your item:” on your terminal
	(3) Then , type new symbol name
	(4) Then , display “Enter initial price of the item :” on your terminal
	(5)Then , type your new initial price

The details of that new item is add to the databse automaticall.

(6) If you enter error letter , you have to connect server b
y command that mentioned earlier.

(7) And also you can see variation of your item in Track.csv file.


