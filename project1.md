[Back to Portfolio](./)

HTML Parser
===============

-   **Class: Data Structures Analysis (CSCI 315)** 
-   **Grade: 100** 
-   **Language(s): C++** 
-   **Source Code Repository:** [alenanicole/HTML-Parser](https://github.com/alenanicole/HTML-Parser)  
    (Please [email me](mailto:andurel@csustudent.net?subject=GitHub%20Access) to request access.)

## Project description

This project is an HTML Parser that completed two tasks for each HTML Page passed to it. First, it will determine if the HTML tags are balanced on the page. Second, it finds the number of unique webpages that can be visited from a certain HTML page. If the webpage is unbalanced, it will not be able to visit any links, and every link must be valid (the page must exist and be passed into the program). A page can visit multiple pages from a single link, if the page that they visit links to another page. However, each page will only count the first time that it is visited. This project was coded in C++.

## How to compile and run the program

First, please download and extract the 'HTML_Parser.zip' file from the Source Code folder. Once you have navigated to the correct directory in your terminal, this project can easily be compiled and ran using a simple make command.

```
make all
```
If you would like to run the program with specific pages, please use:

```
make run
./html-test pages/example_filename pages/example_filename
```
This method can be used to run the program with any number of pages available to the user. These pages currently include index.html, double.html, pokemon.html, notbalanced.html, and theend.html, however, the user can add more to test.

To remove the executable please use:
```
make clean
```
## UI Design

This program will parse the HTML files passed to it and will determine if they are balanced. It will also track the number of unique webpages that the HTML file can visit. The user can run the program with any number of the files provided in the 'Pages' folder, or can create new pages to test.

**NOTE:** This program was made with the intention to parse HTML files that do not contain '<', '>', or '=' symbols anywhere in the file besides HTML tags.

![screenshot](images/test_all.png)  
Fig 1. Testing All Pages

![screenshot](images/test_two.png)  
Fig 2. Testing Only Two Pages

![screenshot](images/test_error.jpg)  
Fig 3. Testing With a File that Doesn't Exist

## 3. Additional Considerations

Sed ut perspiciatis unde omnis iste natus error sit voluptatem accusantium doloremque laudantium, totam rem aperiam, eaque ipsa quae ab illo inventore veritatis et quasi architecto beatae vitae dicta sunt explicabo. 

For more details see [GitHub Flavored Markdown](https://guides.github.com/features/mastering-markdown/).

[Back to Portfolio](./)
