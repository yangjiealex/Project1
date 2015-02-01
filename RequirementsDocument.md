#<center>**Requirements Document -- Team 69**</center>

##1 User 	
###1.1 Software Interfaces

List all the external systems with which the software product interacts. These are external systems/libraries that you have to interact with.

###1.2 User Interfaces

Specify the logical characteristics of each interface between the software product and its users. This is a description of how the system will interact with its users.

###1.3 User Characteristics

Describe those general characteristics of the intended users of the product, including educational level, experience, and technical expertise.

##2 System Requirements

###2.1 Functional Requirements

>####**2.1.1  Application Requirements**
> - The application shall be a command line java based tool used by students to determine the average number of words in a sentence of an essay. 
>- The tool shall be written in Java with no non standard libraries.  
>-  All code that is not part of the Java Development Kit (JDK) shall be included with source code.  
>-  The tool shall be an application and shall have a main method.  

>####**2.1.2 User Execution**
>-  The tool shall compile on the command line using the Java C command with no additional options.  
>-  The tool shall execute from the command line with the Java command.  
>-  The essay shall be a text file.  
>-  The input path file shall be a user input on the command line as part of the application execution.  
>-  The tool output shall be the average number of words per sentence in the essay, rounded down to the nearest integer.  

###2.2 Non-Functional Requirements

>####**2.2.1  Command Line Features**
>-  The user shall be able to specify the minimum number of letters to be considered a counted word using the command line option *-l*	.  
>-  If the user does not specify the minimum number of letters to be considered a counted word the default minimum shall be 3.  
>-  The user shall be able to specify the end of sentence punctuation delimiters using the command line option *-d*.  The optional delimiters shall be comma and semi-colon.  
>-  If the user does not specify the end of sentence delimiter the default sentence delimiters shall be period, question mark and exclamation point.  

>####**2.2.2  Usability**
>-  The developer shall provide a user manual of the tool.  
>-  The tool shall generate a "user friendly" message if the input file is not specified or does not contain words.  
>-  The tool shall generate a "user friendly" message if the compiling of the application fails.  
>-  The tool shall generate a "user friendly" message if the application does not execute successfully.  
