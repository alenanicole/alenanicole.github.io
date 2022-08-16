[Back to Portfolio](./)

UDP File Transfer
===============

-   **Class: Applied Networking (CSCI 332)** 
-   **Grade: 100** 
-   **Language(s): C++** 
-   **Source Code Repository:** [alenanicole/UDP-File-Transfer](https://github.com/alenanicole/UDP-File-Transfer)  
    (Please [email me](mailto:andurel@csustudent.net?subject=GitHub%20Access) to request access.)

## Project description

This project was created to tansfer a file between two computers on the same network using a User Datagram Protocol (UDP) based server and client model. It first creates a connection between a computer running the server program and another computer running the client program. Then, the client will choose which file to send to the server and, if the file exists, will deconstruct the file into packets of 1000 bytes to be sent to the server and reconstructed. This program will work for various file types inclding .jpg, .png, and .txt. This program was coded in C++.

## How to compile and run the program

This project is meant to showcase the transfer of a file between two computers; however, it can also be demonstrated utilizing multiple terminals on the same device. 

If using one device, please download the server.cpp, client.cpp, and makefile files from the provided Github repository. Although there is also a test.jpg file provided to test the program, any file can be used. 

If testing with two computers, please identify which computer will act as the server and which will act as the client and download the appropriate .cpp file and the makefile.

To run the server side please use:
```bash
make server
```

To run the client side please use:
```bash
make client
```

To remove the executable please use:
```bash
make clean
```

## UI Design

Almost every program requires user interaction, even command-line programs. Include in this section the tasks the user can complete and what the program does. You don't need to include how it works here; that information may go in the project description or in an additional section, depending on its significance.

Lorem ipsum dolor sit amet (see Fig 1), consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat (see Fig 2). Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur. Excepteur sint occaecat cupidatat non proident, sunt in culpa qui officia deserunt mollit anim id est laborum (see Fig 3).

![screenshot](images/dummy_thumbnail.jpg)  
Fig 1. The launch screen

![screenshot](images/dummy_thumbnail.jpg)  
Fig 2. Example output after input is processed.

![screenshot](images/dummy_thumbnail.jpg)  
Fig 3. Feedback when an error occurs.

## 3. Additional Considerations

Sed ut perspiciatis unde omnis iste natus error sit voluptatem accusantium doloremque laudantium, totam rem aperiam, eaque ipsa quae ab illo inventore veritatis et quasi architecto beatae vitae dicta sunt explicabo. 

[Back to Portfolio](./)
