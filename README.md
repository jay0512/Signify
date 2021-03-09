# Signify (IMAGE STEGANOGRAPHY APPLICATION)
Signification application using image steganography.


**1.1 Brief Introduction**

In the era of security steganography is the most basic requirement. This project is about hiding any private data inside the image to keep it from eavesdropping.

  

**1.2 Technology Used**

-   Front End: Swing Java
    
-   Back End: Java 8
    
-   Development Tool: Netbeans 8.2
    
-   Diagram Tool: Umlet
   
**Software Requirements Specification**

**2.1 Purpose**

The purpose of this document is to present a detailed description of the Image Steganography Application. It will explain what the system will do, the constraints under which it must operate and how the system will react to external stimuli. This document is intended for end users and the developers of the system.

**2.2 Goal**

To transfer data over network securely and avoid eavesdropping.

**2.3 Product Perspective**

The basic idea behind the idea is to protect the user’s documents using Image steganography and provide an interface to hide and retrieve data.

**2.4 Hardware interfaces**

A Laptop is suitable to the user.

**2.5 Software interfaces**

OS - Any Operating System With JVM
PLATFORM - Java 8
IDE - Netbeans 8.2
Technologies used – Java.

**3.1 System Features**

**3.1.1 Select File to hide in Image**
Description: System provides facility to select the file to  hide into an image.
Input: the file which needs to be hidden in the image.
Output: Display path of the selected file.

**3.1.2 Select Image in which file needs to be hidden**
Description: System provides the facility to select an image  for signifying it.
Input:  Image in which we want to hide the file.
Output:  Display path of the selected Image.

**3.1.3 Hide Data into Image**
Input: Path of the image in which data needs to hide and file which needs to hide into data.
Output:Success message and the name of Signified Image.
Process : Apply the appropriate steganography algorithm according to user’s requirement.

**3.1.4 Retrieve Data from signified Image**
Input: Path of the Signified Image from we want to retrieve the file.
Output: Success message and path of the retrieved file.

  

**3.2 Other Non-functional Requirements**

**3.2.1 Availability**
The application should be accessible from any Computer. The application shall be available 24 X 7.

**3.2.2 Reliability**
This application is reliable and will work on any operating system.

**3.2.3 Security**
Currently, the application does not require the use of a password or login facility. But backtracking of the steganography algorithm is very difficult and hard to predict logic.

**3.2.4 Maintainability**
The system is fully maintainable and can adopt any further changes in terms of features.

**3.2.5 Portability**
Being using java this application in the portable on any os having JVM installed.


**4.1 Use Case Diagram**

![](https://lh4.googleusercontent.com/A_k_8dsMp03k6kckVtTVmtH9EhEBeiD-A6vEp_tN7sha8zhnDTnyRm6Yble1Y69e2lpeKNk_nlYtSmvDoWQYQqwvTBflU4WZyLKcVEalE2ZFVcp1JYYsX4AvTQKySHAYxMQL9CV-)

**4.2 Class Diagram**

![](https://lh6.googleusercontent.com/GMYIML9ah8Uvq-clZIERp-IdhHq9IVULaQp_XiQ-W2gEIWlOy5oYcdw2Ip3079aKt-fgehQh9_5uTsb8--YwIde5Os8QueaxVQGwKtaM8y9s5UEamgsqlTWiLEw_BUDNtKN8eh-i)

**4.3 Hide Data Activity Diagram**

![](https://lh6.googleusercontent.com/K-d9ResF2Asq9BU8Ku2AaUl79h7iCtRajuFA4cm_aXWGLvz8uFa71rAq5mFidb2DJX0tVSFwJb15xlKT2S7rhyaOUtMlsQFuro1jPZnEPtWSwEhksODBR4_6BKOq_ynodYavMRNb)

**4.4 Retrieve Data Activity Diagram**

![](https://lh4.googleusercontent.com/6JbRt00Tm8v1OrSdNvRydeMlCDOvhrVgDYH5UGaqGYzdSZEChQ_dJIGk6oY8YJq8WKT0U39fW41JnaI6FqFnFGBGPDTucl2uZid3eMdgcjwwKqfkcsF3BVkSUgLBhjPaGb5eK3Hj)
