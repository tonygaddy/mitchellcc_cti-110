# CTI-110-MSB2 Notes
## Table of Contents
- Chapter 1
	- [What is a computer?](#what-is-a-computer)
	- [What is a computer program?](#what-is-a-computer-program)
	- [What do programmers do?](#what-do-programmers-do)
	- [Software Development Lifecycle](#software-development-lifecycle)
	- [Writing and Communication](#writing-and-communication)
	- [Programming Languages](#programming-languages)
	- [Compilers and Interpreters](#compilers-and-interpreters)
	- [Client/Server Applications](#clientserver-applications)
	- [Markup languages](#markup-languages)
- [Chapter 2](#chapter-2)
	- [Client/Server Design in Web Applications](#clientserver-design-in-web-applications)
	- [Working with Files and Folders](#working-with-files-and-folders)
	- [Locating Files and folders on Windows](#locating-files-and-folders-on-windows)
	- [Locating Files and Folders on the Internet](#locating-files-and-folders-on-the-internet)
	- [Internet Naming Conventions for Files and Folders](#internet-naming-conventions-for-files-and-folders)
	- [Working with a Local Web Server](#working-with-a-local-web-server)
	- [What Languages Will I Use?](#what-languages-will-i-use)
	- [What Software Will I Need?](#what-software-will-i-need)
	- [Using Your Web Server](#using-your-web-server)
	- [Using URLs with your Web Server](#using-urls-with-your-web-server)
	- [Always Use URLs to Run Your Web Applications](#always-use-urls-to-run-your-web-applications)
	- [Where to Save Your Work Files](#where-to-save-your-work-files)
	- [The Importance of Frequent Backups](#the-importance-of-frequent-backups)
	- [Creating an HTML Document](#creating-an-html-document)
	- [Creating a PHP Program](#creating-a-php-program)
	- [Creating an Interactive HTML and PHP Program](#creating-an-interactive-html-and-php-program)
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
## Chapter 2
### Client/Server Design in Web Applications
- Client Programs(Web Browser)
	- Send requests to server programs to perform a tasks
	- Web browsers send requests to Web Servers
		- examples include: visiting a link or submitting a form
- Server Programs(Web Server)
	- Receive requests, process them, and respond appropriately
	- Server applications may also make requests of other applications during
	  processing
	- May respond to hudreds or thousands of requests
	- Web server response is *typically* a web page
- Web-based applications:
	- Require no special software for users
	- Can be updated without requiring access to the end users computer
### Working with Files and Folders
- Computer files contain data of some kind: an image, video, document, executable code, etc.
	- File extensions are used to indicate the type of data contained in the 
	  file:  
	  | _File Type | Extension | Editor     | Viewer      |
	  |:----------:|:---------:|:----------:|:-----------:|
	  | _Jpeg Image| .jpg      | Paint      | Photos      |
	  | _Mp3 audio | .mp3      | Audacity   | Groove      |
	  | _Zip file  | .zip      | 7zip       | 7zip        |
	- File types we will use:  
	  | _File Type | Extension | Editor     | Viewer      |
	  |:----------:|:---------:|:----------:|:-----------:|
	  | _Text file | .txt      | Text Editor| Text Editor |
	  | _HTML file | .htm      | Text Editor| Browser     |
	  | _CSS file  | .css      | Text Editor| Browser     |
	  | _PHP file  | .php      | Text Editor| Web Server  |
- Files are typically organized into folders(aka directories) for easy file 
  management
	- Files and folders are stored on protable or fixed disks and accessed via 
	  disk drives
	- Local disks are attached directly while remote disks are attached to the 
	  network
- In order to locate files, we need an addressing scheme
### Locating Files and folders on Windows
- Windows uses the disk drive as the root of the file addressing
	- this is followed by a list of folders
	- And finally followed by teh name of the file itself
	- for example:  
	D:\CourseMaterial\Coursework\wage1.html
### Locating Files and Folders on the Internet
- Internet addresses are based on the IP(Internet Protocol) addressing scheme
	- An IP address is a unique series of numbers that point to a folder on a web 
	  server, example 128.30.52.100
	- Since it would be difficult to use this address every time we wanted to access a web site, we use domain names instead(www.w3.org)
- So, a domain name refers to an IP address
	- A URL(Uniform Resource Locator) consists of:
		- A domain name(www.php.net)
		- A list of folders(if any) to get to the file
		- lastly, the file name and extension of the resource we want to request
		- For example:
		http://www.php.net/license/index.php
		- Where www.php.net is the domain name
		- license is the folder
		- and index.php is the name of the file we are after
		- Note: typically, if no file name is requested, the web server will 
		  return a default document (like index.php for php servers)
- Internet addresses use a forward slashes(/) while Windows will use either a forward or back slash(\)
### Internet Naming Conventions for Files and Folders
- When naming files for use on the internet:
	- Use descriptive names
		- tax-report-2016.html not tr16.html
	- Avoid very long file names
	- Use hyphens, not spaces or underscores, between words
	- Use lower-case instead of upper-case letters
		- Some server environments are case sensitive
### Working with a Local Web Server
- Since we are installing and running our Web server locally, we don't have to 
  be connected to the internet to work on our code exercises
- We will use a special loopback address and domain name to reference our local
  server
	- The domain name is localhost and is on IP address 127.0.0.1
	- Our URLs will look like:
	http://localhost/webtech/samples/my-web1.php
### What Languages Will I Use?
- We will create the structure for our user interfaces using:  
  HTML(Hypertext Markup Language)
- We will apply formatting and style to the interfaces using:  
  CSS(Cascading Stylesheets)
- For receiving and processing input as well as returning results, we will use:  
  PHP(PHP Hypertext Processor) programming language
- Finally, To store and retreive data, we will use:  
  MySQL(Structured Query Language)
### What Software Will I Need?
- A text editor to edit code
- A Web server to enable PHP processing
- A Web browser to view created applications
### Using Your Web Server
- This course is designed to make use of a local, standalone web server
	- The exercises can be completed without an internet connection
	- The server is portable and can be executed from a removable drive
	- This type of environment is often used by professional web developers when
	  designing and testing web applications
### Using URLs with your Web Server
### Always Use URLs to Run Your Web Applications
### Where to Save Your Work Files
### The Importance of Frequent Backups
### Creating an HTML Document
### Creating a PHP Program
### Creating an Interactive HTML and PHP Program


