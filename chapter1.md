# CTI-110-MSB2 Notes
## Chapter 1
### What is a computer?
- A computer is a *programmable machine*

### What is a computer program?
- A collection of commands that directs a computer's *Operating System(OS)* and 
  hardware for a specific purpose. Examples:
	- Display a picture
	- Save a text document
	- Send a print job to a printer
- The collection of commands that the computer's microprocessor can execute.
	- The microprocessor has a built-in set of commands that together are its
	  *instruction set*. Examples of these commands include:
		- Adding two numbers
		- Performing a logical comparison
		- Moving data from one memory location to another
	- The OS provides a friendlier interface to run the machine language 
	  commands that the computer actually understands.
- A computer program, like your web browser,  is a collection of these commands
  that is being executed by the operating system.
	- Computer programs will most often do one or more of the following things:
		- Provide text-based or Graphical User Interface(GUI) commands for users
		- Read and/or write data
		- Perform calculations
		- Process text
		- Communicate with other programs or devices
		- Control hardware
### What do programmers do?
- Evaluate software requirements
	- Effectively communciating with users to gather information about software 
	  needs
	- It is important to take your time, read any requiremetns documentation 
	  carefully, and ask questions if needed for clarification.
	- Do not rush through the early stages of software development so that you 
	  can just get to the code.
- Design software
	- Creating user interfaces and breaking down tasks into modules.
	- Modular design enables: concurrent development, reusable code, and 
	  individual testing of modules.
	- Spend time in this creative stage to develop new and innovative ideas.
	- The design stage is an opportunity to use your right brain before getting
	  into the more left brain coding phases.
- Develop algorithms
	- Steps or instructions for the application to follow (written in 
	  *pseudocde*), to fulfill software requirements.
- Write code
	- Translating *pseudocode* into a programming language
	- Includes commenting, documenting, debugging, and testing code
- Application testing
	- Thorough, end-to-end testing of the completed application
	- Should also test for usability of the application, to make sure the 
	  application can be easily understood
- User support, training, maintenance
### Software Development Lifecycle
1. Evaluate Requirements
2. Application Design
3. Algorithm Development
4. Application Coding
5. Application Testing
6. User Support, Training, and Maintenance
### Writing and Communication
Effective communication is a highly valuable skill for programmers:
- Gathering software requirements:
	- Being a good listener
	- Asking open-ended questions
- Documenting code:
	- Concise code comments
	- Comprehensive user documentation
- User support and training:
	- Articulate speech
### Programming Languages
- A high level programming language is a human readable language with keywords 
  and symbols used to issue commands via the OS to the microprocessor.
- Coding is the act of creating source code with a programming language.
- Source code is the file or files that contain programming instructions for a 
  specific purpose.
- Before being executed, these commands are translated into machine language, 
  the only language that microprocessors understand, using either a compiler or
  an interpreter.
### Compilers and Interpreters
- Compilers create executable files that contain commands in machine language 
  from source code (programming instructions).
	- Compiled code is usually faster.
	- Another advantage is that the end user does not have access to the source 
	  code and cannot make changes to the program.
	- One disadvantage is that the code must be compiled for each platform on 
	  which it will run.
		- Different computers will have different processors and/or OSs. 
		- This mean they may have a different instruction set, or different
		  methods of calling those instruction set commands.
- Interpreters translate source code into machine language when the application 
  is requested.
	- Interpreters normally run on a server so application updates are easier.
	- They convert the server code, written in a high level programming 
	  language, into executable machine language, one line at a time.
	- The iconic example would be a web application, which is an examlpe of 
	  *client/server* design.
- The Java programming language is an example of a hybrid of these two systems.
	- Java source code is partially compiled into bytecode, which is interpreted
	  by the Java Virtual Machine(JVM) which passes the commands to the 
	  microprocesser.
### Client/Server Applications
- In this course, we will be creating client/server web applications
	- In these types of applications the client application (web browser) calls
	  on the server with a request, then the server application (PHP hosted on 
	  Apache) sends a response.
- This is in contrast to stand-alone applications, which run entirely on your 
  system.
### Markup languages
- Markup languages are used to format the presentation of data.
	- Markup languages are a great compliment to programming languages, which
	  are used, in part, to manipulate data.
- We will use HTML (Hypertext Markup Language) to create a GUI into our PHP
  (PHP: Hypertext Preprocessor) applications.
	- HTML is a declarative markup language that uses <tags> to define the 
	  structure of documents and data.

