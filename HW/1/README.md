#Exam Questions <img src="../../Resources/exam.png" width=50px alt="Tick Sheet">




##Instructions

Edit this document and answer the questions in the sections surrounded by ```.




There are **24** marks available and are awarded grades as follows:




|Score|Grade|

|-----|-----|

|<3|U|

|5+|G|

|7+|F|

|9+|E|

|11+|D|

|13+|C|

|15+|B|

|17+|A|

|19+|A*|







##Data Representation




###1 - Why do we represent data using binary when using computers *(1 mark)*




```   

because computers do tasks in the form of on or off. (1 equals on and 0 equals off)

```

###2 - How would we represent the number 147 in binary? *(1 mark)*

```

10010011

```

###3 - Can you convert the hexadecimal number **b5** to denary, there is a mark for you working. *(2 marks)*

```

b = 11, 11 + 5 =16 or 00010000

```

###4 - Here is a function written is **pseudocode**.

```

FUNCTION validUser (users , user)

    FOR x <-1 to LEN(users)

        IF users[x] = user

			RETURN True

		ENDIF

	ENDFOR

	RETURN False

ENDFUNCTION

```




(a) What type of data is **users**? **(1 mark)**

```

variable, string

```




(b) What type of data is returned by this function? **(1 mark)**

```

boolean

```




##Errors

###6 - This program is supposed to find the mean of a list of numbers and print it out for the user:

```

line1:		tot <- 0

line2:		nums <- [1,6,4,2,5,3]

line3:		FOR x <- to LEN(nums)

line4:			tot <- nums[x]

line5:		ENDFOR

line6:		mean <- tot

line7:		OUTPT mean

```




(a) On which line is there a **syntax** error? **(1 mark)**

```

6

```




(b) What is meant by a **syntax** error? **(1 mark)**

```

An error that will stop the code because it doesnt know what to do

```




(c) Identify a logical error in the program and suggest how this might be fixed. **(2 marks)**

```

line 6 it tells the computer that mean = total when it shouldnt it should be mean = tot / nums. 

```




(d) Describe and give an example of the 3rd kind of programming error. **(2 marks)**

```

run-time. when you call a variable by its wrong name later on in the code, it will go and do everything before it until it gets to that point

```




##Algortithms

###7 - Write an **algorithm** that if given a list of numbers could find the largest. Try to use [pseudocode](http://filestore2.aqa.org.uk/subjects/AQA-GCSE-COMPSCI-W-TRB-PSEU.PDF).

```

  i = i+1 

  while i < N 

     if A[i] > A[i+1] 

          swap A[i], A[i+1] 

     end if 

  end repeat 

end repeat 




```




##Networking

###8 - Research the following methods (*topologies*) for connecting devices to a network. In each case give a description and at least 1 advantage and 1 disadvantage.




**Bus Topology (6 marks)**

```

Describe: All nodes are connected to a single cable from the help of interface connectors. This is the "backbone" of tne network and is therefore known as the bus




Advantages:Easy to set up,

Is very cheap compared to others




Disadvantages: Security is not very strong because all of the computers recieve the sent signal.

```




**Ring Topology (6 marks)**

```

Describe: where the devices are connected to each other in a circular direction, each packet is sent around the ring until its final destination has been reached




Advantages: Data is transferred very quickly

Adding more nodes has little impact on bandwidth




Disadvantages: Difficult to troubleshoot the ring

Total dependence on the one cable

```




**Star Topology (6 marks)**

```

Describe: Where the devices on network are connected to a central hub




Advantages: Good performence

Easy to set up and expand




Disadvantages: Expensive to install

Extra Hardware required

```
