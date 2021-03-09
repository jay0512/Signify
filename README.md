# Signify (IMAGE STEGANOGRAPHY APPLICATION)
Signification application using image steganography.

Demo Video: https://www.youtube.com/watch?v=wIya4Tzkytc

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

  
 **5.1 Unit & Integrity Testing of Software**

**5.1.1 Test Case 1**
| Parameter name | Value | Description |
|--|--|--|
| File path  | /home/user1/Desktop/SRS_Signify.doc | Path of Image in which file needs to be hidden. |
| Image path | /home/user1/Desktop/DSC7632.jpg | Path of the file which needs to be hidden in an image. |
|Signification Preference| Basic| The security level of Steganography algorithm|
| Message | Data Hidden Successfully. | Success Message.|

**5.1.1 Test Case 2**

| Parameter name | Value | Description
|--|--|--|
| File path | /home/user1/Desktop/6K7A8924. | Path of Image in which file needs to be hidden.|
| Image path | /home/user1/Desktop/DSC7632.jpg |Path of the file which needs to be hidden in an image.|
|Signification Preference|Basic|The security level of Steganography algorithm
|Message|Too big file to hide in an image.|Failure Message due to oversize of a document file.

  
  

![](https://lh4.googleusercontent.com/suTxyD43aDyWXd-kg0SfSbvN8GFTg44e0QbDf3XDC3TPBs_XFRrIorKVPN6O1FQXIb1KDEKIf-t8M86cxCIuv0aCmOcx4gkVxqAyGFYjfLspdiU3islePVmkSUgd6ehXKDgkxSsz)

Figure 1 : Hide Data Screen with success message

![](https://lh3.googleusercontent.com/kWdJg4yNdZTQnt0Yxdtb_tSPZUhC_k9XYygZxKpaXHOgFSvln3AtWG6uaBMubH3bX5IUX-rR-5V8T4W2RHiygRF88ZzDW2riIvEZXstuGdZxFwZkhPF3R6GUpoX2JilCQhfiaFm3)

Figure 2 : Retrive Data Screen with retrived File name

  
  
  

![](https://lh4.googleusercontent.com/50pP8UouS3lcNxjchi6Q8R8Ggyv9s2FGxtM9UuVdfjvCtY1I9XHpzBw3T_eOPatMSm1ZMG6bd-h_EhqlZfZqwME831ldwdDXI3zTcS2vkrfDmq1GbMAb8o2o9RotiA4h2YecC3AN)

Figure 3 : Error message due to choice of too big file to hide in the image.

![](https://lh4.googleusercontent.com/Rqna21POe26LInTJHl8chiEoNYL_85ead9H1SrRz8fSwpLASmfqWrxO_8NsTGawbJdA1fXNgAxVaZC-aubodcAaeJHLC3jqZQEOIFY5ELpduHtUtfg-9rCdSPkp27HQw7_Ao2jGR)Figure 4 : Password Screen for modrate security.

![](https://lh5.googleusercontent.com/5SOS2I_noaS1Oc6imbO7DRREIRYCWd5bT6edp0bFppL3QmT3NJME0kJmBDSnceRShBvvtLIj8bP9Aw29cM06HvLYjLI7XgPO93eoKlV2-TsYSCR8VT0boqVj5PT8IH35Wx2W15GW)Figure5 : Original Image.![](https://lh6.googleusercontent.com/s18EfWJEq4TmHo49Cwawg9Z7bnpzcNAinAVL--zLtbwY8ChN5syZuVuqBB0y0dCY6jzs9GUh052_JIpNL1j6aSi8UvdjYuBHgiNQ7rTJ4SR1lDQY78JHy9LRK824dtdfrvQI8WUG)

Figure 6 : Signified Image( Contains Hidden data )

  
  
  
  
  

**6.1  Conclusion**
Nowadays network security is a major issue, And hiding data is necessity. So this project can be helpful to deliver to intended person over the network with very less probability of it being stolen as its hidden inside the image and Bruteforce attack will take time as in the keyed method of data hiding as the key is of 7 digit alphanumeric (52+10=62 characters) as well as special characters (33 characters) the bruteforce attack will take 69,833,729,609,375 iterations which will take approximately 8 days in morden computers.Hence, this project Chip In a bit in image steganography.

**Future Extension:**

This project can be further extended by making it as peer-to-peer secure file sharing application where the receiver’s hardware address will be there in encrypted form within the image and which will be used to decide whether or not to show the data behind the image to the particular receiver. Hence there won’t be very minimal chances of eavesdropping unless noted otherwise.
