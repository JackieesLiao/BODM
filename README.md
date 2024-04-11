# BookOfDonationManagement_WechatMini
##  Configuration required for compilation:
###  Operating system: win 10
###  Develop tools:
     Front-end: WeChat developer tools
     Backend: IDEA LatestVersion
     Database: Navicat for MySQL  
### Development environment configuration
      JDK1.8
      Apache-tomcat-8.5.82
      MySql 5.7
### Development language:  
Frontend: JavaScript && CSS  
Backend: Java    
Database: MySQL        

# Functional division    
## Book   

If you can't log in, check whether the pom file is red and whether the database configuration is correct. The picture folder is re-added in the tomcat configuration.    

Use the tutorial idea to run the shequ file. Change the username and password in jdbc.properties to your own database username and password.   
<img width="935" alt="144386118-ca647489-d1a0-4613-bbcd-3aaec32b9f37" src="https://user-images.githubusercontent.com/85597324/145163152-fa5f3f79-720a-447e-9bdb-2861030905d0.png">   

Navicat software mysql imports and runs sql database files     

WeChat developer tools run frogla files    


The user role design analysis of this book donation management system is divided into two parts. According to the different roles of different users, the system is designed with use cases to pave the way for subsequent design.    
This system is mainly divided into ordinary users and administrators. Ordinary users mainly use WeChat mini programs systematically. The administrator mainly manages all the information in this book donation management system, including the information involved in the user part.    

The main functions of mini program front-end users are:
1)Register and log in. Ordinary users can fill in the information to register and log in to enjoy the functions.   
2)Article viewing, ordinary users can view published articles.   
3)Feedback: Ordinary users can provide feedback on the use of mini programs.   
4)Book viewing, ordinary users can see all donated book information and query according to the provided book number.   
5)Book collection, ordinary users can collect donated books.   
6)Announcement viewing, ordinary users can see the announcements issued by the administrator.      

The main functions of the backend manager are:
1)Article addition, the administrator can add articles to the mini program based on the submitted articles.    
2)Book addition: Administrators can add donated books to the mini program based on donor information.    
3)Book collection, the administrator can query the user's collection of books.   
4)Feedback: Administrators can query user feedback content.   


## Introduction to front-end operating effects

### A) Home page function
The homepage of the book donation management system applet system consists of three parts, namely homepage, announcement, and mine. The home page is the most important part of the system, providing article reading, feedback and book query functions. The page displayed after entering is as shown below.    
![image](https://user-images.githubusercontent.com/85597324/145163998-cf4743d7-1161-41bb-b4f2-fdc0a761823a.png)


### B) Article function   
The modification function mainly implements article reading. After the article is reviewed and published by the administrator, users can select and read articles under the modification function.    
 ![image](https://user-images.githubusercontent.com/85597324/145164011-4bd5a9fd-6669-4d51-8eae-b839b94b8629.png)


### C) Books function    
This function is the main module of this system and needs to be logged in before it can be used. It consists of four functional modules, namely book list, book details, book search and book collection.      
1)The book list is reviewed by the administrator and released related information about donated books. Users can select donated books under the modified function to view details.    
2)For book details, the user can click on the detailed view function to view the donor's profile of the donated book, book message and book donation time, as well as the immediate collection function.   
3)Book collection allows users to click Collection Now to collect their favorite books.   
4)In the book search, the user enters the book number to accurately retrieve the book list, and the search jumps to the book details page corresponding to the book number.   
 
![image](https://user-images.githubusercontent.com/85597324/145164050-cb6e16b4-15fb-4481-a3fd-c027f3bfd716.png)
![image](https://user-images.githubusercontent.com/85597324/145164063-eadd439c-305b-4dae-9644-2db48e586469.png)
![image](https://user-images.githubusercontent.com/85597324/145164074-3f87e844-5b2a-4cbd-9ec6-90bb58a46df2.png)
![image](https://user-images.githubusercontent.com/85597324/145164086-acdecee0-ab7b-45ed-880f-16fb2241c6af.png)


### D) Opinion function
This function mainly allows users to provide feedback on software usage problems and software usage problems. 
The feedback content can include text and pictures. After the feedback is given, the administrator will review and process it in the background.       
 
![image](https://user-images.githubusercontent.com/85597324/145164110-2f192208-8aa2-4415-96eb-f1edceebe214.png)


### E)Announcement function
Announcements are issued by the administrator, and users can view the announcement content at any time.     

 ![image](https://user-images.githubusercontent.com/85597324/145164125-79f0419c-e3b1-437c-835c-b6a378411968.png)


### F)My functions
It mainly implements user login and registration functions and my book collection viewing function.    
 ![image](https://user-images.githubusercontent.com/85597324/145164134-e7116098-11db-42f2-885c-335ffbbfefbe.png)   

### G)Registration function
This function mainly requires users to fill in their gender, select their gender, select their school room number, mobile phone number and password to register.   
 ![image](https://user-images.githubusercontent.com/85597324/145164151-f35dc404-a71b-4b52-b5b4-2e606cd5e6eb.png)   


### H)Login function  
This function mainly requires users to log in by entering the mobile phone number and password used during registration.    
 ![image](https://user-images.githubusercontent.com/85597324/145164165-c8683ccd-9e20-4ac4-afa5-fe1abc9e3eef.png)


### I)Collection function   
The modified function is mainly for users to view the collected books and view the detailed functions of the books. This function requires logging in before it can be used.    


![image](https://user-images.githubusercontent.com/85597324/145163392-cae41d3f-fccb-49c5-8098-dafb495b78d0.png)   

## Introduction to back-end operating effects

![image](https://user-images.githubusercontent.com/85597324/145164268-c8691791-ee7e-4511-b1c1-2131a90682ba.png)
![image](https://user-images.githubusercontent.com/85597324/145164296-5a0e49a7-6a36-4cfc-b1d5-f59ebbdd81b6.png)
![image](https://user-images.githubusercontent.com/85597324/145164306-c9bd20bf-5e71-4ed4-a7d9-5625d4338102.png)
![image](https://user-images.githubusercontent.com/85597324/145164319-3a2de303-a29f-4f91-bb46-dc9486d618ac.png)

