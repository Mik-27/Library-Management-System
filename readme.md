# Libray Management

This application provides an interface for issuing books. It contains both the student as well as the librarian side interfaces. Students can isuue books while the librarian can see which books have been issued and the act accordingly.

## Getting Started

Application can be downloaded simply through git. The 'Executable JAR File' in ```Library Management/dist```  can be executed to run the application. Apache Netbeans can be used for efficient running as well as modifications in this.

# Prerequisites

A set of files need to be included for connectivity between MySQL and the JAVA application:
```
jackcess-3.0.1.jar
commons-logging-1.2.jar
commons-lang-2.6.jar
ucanaccess-4.0.4.jar
hsqldb-2.5.0.jar
```

# Files

The ```.xml``` file are the graphical preview of the program in the ```src/javaproject``` folder.
```.java``` are the program files that contain the main program, connection with thee database and styling of the application.
```icons``` folder in src/javascript contains the various icons that are used in the application. ```db``` folder contains the database files for the login as well as the books issued. ```img``` folder contains the background image that is used.

## Description

User can login if he/she has been registered or he/she can register themselves through the registration form. Librarian can login through the librarian login which will direct him to the librarian end of the application.

# Student Interface

On the starting page after login students can view the books that are available along with their details by clicking on the ```Books``` tab on left side of the app. Students can issue books through the ```Issue Books``` tab. Student cam issue a book by entering the Book ID and his/her username. Note that a student cannot isuue unavailable books and even issue books more the once.

# Librarian Interface

Starting page for the librarian displays the books that are available in the library. The Librarian can add or remove books according to him/her. The Issued Books tab displays the books that are issued by the users so that the librarian can act accordingly.

## Built in

[Apache Netbeans](https://netbeans.apache.org/) - IDE used.

## Built with

[JAVA](https://www.java.com/en/) - Language used.

[MySQL](https://www.mysql.com/) - Database used.

## Authors

* **Mihir Thakur** - [Github](https://github.com/Mik-27)
* **Anand Tiwari**
* **Abhishek Walinjkar**
