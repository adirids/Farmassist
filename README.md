# Farmassist
Client-Server for farming
## FARMASSIST-Connecting farmers through multithreading

OS concepts of multithreading and  inter-process-communication are being used in this work.

### INTRODUCTION
A thread is a single sequence stream within a process which can be managed independently by a scheduler. Also known as lightweight processes, threads allow multiple execution of streams. They made an early appearance under the name of tasks in OS/360 Multiprogramming with a Variable Number of Tasks in 1967 until Victor A. Vyssotsky named them threads.
Initially the concept of single-threading was implemented. Single-threading is the processing of one command at a time i.e. the work is completed as a single stream of instructions in a certain amount of time.  However, this wasn’t efficient enough and a new concept called multithreading was developed. Multithreading is a widespread programming and execution model that allows multiple threads to exist within the context of one process. These threads share the process's resources, but are able to execute independently. It proved to be advantageous over single-threading due to the following reasons:
•	Faster execution: As the threads of the program naturally lend themselves to parallel execution assuming sufficient independence, it operates faster.
•	Better system utilization: A file system using multiple threads can achieve higher throughput and lower latency since data in a faster medium can be retrieved by one thread while another thread retrieves data from a slower medium with neither thread waiting for the other to finish.
•	Parallelization: Data and tasks are split into parallel subtasks and the underlying architecture manages how the threads run, either concurrently on one core or in parallel on multiple cores.
•	Responsiveness: Multi-threading can allow an application to remain responsive to input. In simpler words, if threads are blocked, another thread can still run and finish a task.
This work implements the concept of multi-threading by assigning a thread to a farmer each time he wishes to communicate with a fellow farmer.
Secondly, Client-Server model has been used which is basically an application structure which provides service or resource through servers to those who need the services-Clients. It is basically an application that runs on remote servers for providing info, Client-Server application requires an interface through which the client may interact with the servers. It is usually browser controlled application and hence it is programmed in a language which is browser understandable which in this case is JAVA.Since it has to be installed on both machines/devices hence it is known as Two tier system.
We are also making use of the concept of inter-process-communication. Inter- process- communication basically deals with sending and receiving of messages between processes. There are two basic mechanisms to it.In mechanism (a) the messages are passed on by both the processes to a buffer from which both the processes communicate and pass the messages to each other.
In mechanism(b) the messages are passed on to a shared memory.The usage of mechanism (b) has been implemented in our work where the server acts as a common medium between the farmers and the authorities operate the server. 
2.RELATED WORK
There is no direct work available related to this project on internet. However, a similar base concept of chat model has been implemented beforehand, in many languages. Secondly, there are many apps for farmers related to best agricultural practices .The list of some of these applications is given below:-
•	KISAN SUVIDHA-many features need by the farmers
•	IFFCO KISAN AGRICULTURE-government app
•	RML FARMER-KRISHI MITR-provides help in terms of crop loans and guides them
•	PUSA KRISHI-concentrating on crops
•	AGRI APP -concentrating on crops
•	KHETI BADI- concentrating on crops

Most of these apps focus on the crop aspect of farming with none of them focusing clearly on disaster management aspect of farming. 
2.1 Advantages of these applications for farmers
1)	They help the farmers to decide which crop to cultivate
2)	They help the farmers know the proper selling price for their crops
3)	They help farmers take interest free loans
4)	They help them raise their voice for compensation
5)	They guide them about exporting their crops

2.2 Disadvantages of these applications
1)	Help never reaches on time
2)	Thousands of farmers die every year
3)	Most farmers can’t understand these apps
4)	Many farmers don’t have smart phones

Coming to the client server chat model it is a working model in countries like USA where the literacy rate is quite high. Farmers  have access to mobiles. They have proper connectivity. They know how to approach the authorities. The authorities too are quite aware about the need of the farmers. 
The use of client server chat model by farmers in India isn’t that successful as the literacy rate is low.  They can,t use these apps as they are not able to understand these complex apps. Hence this project proposes an image based app which will help the farmers.
