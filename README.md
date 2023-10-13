# python-basic-to-adv
python core to advanced
PYTHON
# Introduction
•	python is a general purpose high level programming language
•	python was developed by Guido Van Rossum in 1989 while working (NRI)national institute of Netherlands
•	But officially launched in to public 1991: DOB 20-02-1991
•	python is easy learn and easy to understand and easy to deploy
eg: 1) To Print “hello world”
in python syntax is 
print(“Hello World”)
# output 
	Hello World
•	Monty Python’s is famous tv show in netherland broadcast in BBC 1969-1974
	FEATURES FROM DIFFERENT LANGUAGES LIKE….
1.	Functional programming features from C.
2.	OOP concept features from C++.
3.	scripting language features from Perl and Shell script.
4.	Modular language features from Modula-3.
5.	Most syntax derived from C and ABC languages


where we can use Python: 
1.For developing Desktop,Web,Database,ML,AI,Data analasys Application.
2.its can use also NASA , NSE (National stock Exchange),Google,youtube.
3.software companies like IBM, Microsoft, Yohoo…..etc
FEATURES OF PYTHON
1.	Simple and easy to learn:
python is a simple programming language.we can feel like read English
The syntaxes are very easy and  (30+) key words are available.
very less no.of lines and simplicity and readability
we can reduces cost of projects
2.	Freeware and open source 
its available free in internet andwithoout any  licence we can use it.
3.	high-level programming language
high-level programming language It is programmer friendly language 
4.	plat-form independent
python code – PVM – operating system(Mac,windows,linux) - hardware
5.	Portability
python programs are same results in if any operating system so it is portable
6.	Dynamically type
In python we are not required to declare type for variables.
whenever we assigning the value , based on value,type will be allocoted automatically 

7.	procedure oriented and object oriented
python languages support procedure and object oriented
 PO extracted from Pascal and C , OO extracted fron C++,Java hence we can get both benefits security and re-usabilty
8.	Interpreted
its totally excuted from PVM 
9.	Exetensible.
we can use already excisting legacy non pythoncode
we can improve performance of the applications 
10.	Embedded
we can any  python programs in other languages
# FLAVOURS OF PYTHON
1.	.Cpython
2.	Jython
3.	Ironpython
4.	pypy
5.	ruby python
6.	anaconda python
# VERSIONS their realases
1.0	in 1994
2.0	oct-2000
3.0	dec-2008


**IDENTIFIERS**
It can be class name or variable name or module name or char name
RULES :-
	 its starts with only Letter or _ underscore
	cannot start with the numeric digits
	no symbols doesnot starts with it. 
  # RESERVED KEY WORDS
 	True, false, None 
 	and, or, not, is
 	if, elif, else
 	while, for, break, continue, return, in, yield
 	try, except, finally, raise, assert
 	impot, from, as, class, del, pass, global, nonlocal, del, with, lambda
# DATA TYPES
1.	Numaric –int, float, complex
2.	Boolean—True, False, No
3.	Sequance  --string, list, tuples
4.	Dictionary
5.	Set 
  #        CASTING,COMMENTS
	Single comment --#
multiple comments --```        ```
Numaric –int, float, complex
int:- its allows only integers
float:-- its allows only decimals
complex:--a+bj (a represents realpart b is imaginary part)
                  a,b contains only integers and floats
1.	BOOLEAN :                      
                           If x int data type
                            0 is false 1 is true
                             
                             if x float data type
                                  otherwise one (true)
BOOLEAN :

                      if x is string data type
                      if x is empty string false otherwise true

                     if x is complex type
                     if both R & I parts are zero 0+0j
                     then the result is  otherwise the true  
      
	**FUNDAMENTAL DATA TYPES Vs IMMUTABILITY**
•	all fundamental data types are immuatable once we create ,we cannot change 
•	if we trying to change the new object wil be created
•	these non chanagable behaviour are called immutable
     **  # BYTES DATA TYPES **
•	Bytes data types represents a group of array byte numbers just like an   
eg😊 1 x = [10,20,30,40]
            2 b=bytes(x)
            3 type(b)       bytes
                                     4 print b(0)  10
                                     5 print b(-1) 40 
# List data types: mutable  [ ]
if we want to represents a group of values a single entity where insertion order required to preserve and duplicates are allowed
1.Insertion order is preserved
2. Heterogenous objects are allowed
3. Growable in nature
4. Duplicates are allowed
5. Values should be Enclosed ] [ 
Eg: List = [10,10.5,Mahesh,Abraham,10,”sai”,true]
      print(List) [10,10.5,Mahesh,Abraham,10,”sai”,true]
# Tuple data types: immutable  ( )**
 Tuple data type is same as well as list data type except it is immutable  I.e we cannot change the value. its represents as paranthesis
Eg t= (10,20,30,40,50)
     type(c)  <class Tuple>
      this error like Attribute error
# Range data types: : immutable  ( )
Range data type means sequence of numbers
the  element present in this data type is not modifiable
Eg: range(10)   0 to 9
1.	r= range(10)
2.	for i in r
3.	print(i)    0,1,2,3,4,5,6,7,8,9
4.	r= range(10,20)
5.	for i in r
6.	print(i)    10,11,12,13,14,15,16,17,18,19
7.	r= range(10,20,2)
8.	for i in r
9.	print(i)    10,12,14,16,18.
# set data types: mutable  [ ]
if we represent a group of values without duplicates where order is not important then that will be go for set types
1.	insertion order is not preserved
2.	Duplicates are not  allowed
3.	heterogenous objects are allowed
4.	index concept is not applicable index nothing but for s[-1] or s[1] 
5.	it is mutable collection
6.	growable in nature
1.	S=(100,10.5,52,Aravind)
2.	print(S) (100,10.5,52,Aravind)
3.	S[0]  type error ( becoz its not supported to indexes)
4.	S.add(60)  (100,10.5,52,Aravind,60)
5.	S.remove(100)  (10.5,52,Aravind,60)
# Frozenset data types: : immutable  { }
its is as it is same to set data type but we cannot add and remove functions
1.	S={ 10,20,30,40}
2.	Fs -frozenset(s)
3.	type(fs) <class  frpzenset.
4.	fs.add(70)  type error
# dictionary data types:{ } mutable
if we want to represent a group of values and key pairs then we should go for dictionary data types
1.	d= {101:’mahi’,102:’aravind’,103:’abraham.}
2.	type(d)   < class’dict’>



         









 



 




