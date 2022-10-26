[Back to Portfolio](./)

UDP File Transfer
===============

-   **Class: Applied Networking (CSCI 332)** 
-   **Grade: 100** 
-   **Language(s): C++** 
-   **Source Code Repository:** [alenanicole/UDP-File-Transfer](https://github.com/alenanicole/UDP-File-Transfer)  
    (Please [email me](mailto:andurel@csustudent.net?subject=GitHub%20Access) to request access.)

## Project description

This project was created to tansfer a file between two computers on the same network using a User Datagram Protocol (UDP) based server and client model. It first creates a connection between a computer running the server program and another computer running the client program. Then, the client will choose which file to send to the server and, if the file exists, will deconstruct the file into packets of 1000 bytes to be sent to the server and reconstructed. This program will work for various file types inclding .jpg, .png, and .txt. This project was coded in C++.

## How to compile and run the program

This project is meant to showcase the transfer of a file between two computers; however, it can also be demonstrated utilizing multiple terminals on the same device. 

If using one device, please download the server.cpp, client.cpp, and makefile files from the provided Github repository. Although there is a test.jpg file provided to test the program, any file can be used. 

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

This program can be used to transfer data between two computers with one acting as the server and the other one acting as the client. This program contains little user interaction, only requiring the user to choose a port, input the IP address of the server, and designate which file is being sent. The program will then determine if the connection between the server and the client has been made and send the file to the server.

![screenshot](/images/make_server.png)  
**Fig 1. Setting up the server**

![screenshot](/images/make_client.png)  
**Fig 2. Setting up the client**

![screenshot](/images/error.png)  
**Fig 3. Feedback when an error occurs.**

![screenshot](/images/dummy.jpg)
**Fig 4. The file is sent to the server, and appear on the server-side device**

## Demo
[![File Transfer Demo](https://res.cloudinary.com/marcomontalbano/image/upload/v1666808822/video_to_markdown/images/youtube--2DGleVhrsKw-c05b58ac6eb4c4700831b2b3070cd403.jpg)](https://youtu.be/2DGleVhrsKw "File Transfer Demo")

## 3. Additional Considerations

This project could not have been completed without the assistance of my partner, Amber Livingston.

[Back to Portfolio](./)
