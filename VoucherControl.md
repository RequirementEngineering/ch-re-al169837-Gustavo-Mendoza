## Introduction 
  The place where I work we have a voucher system also we want to improve reducing the paper to have a better control and managment. It make a inventory where all the voucher storage into a DataBase with that in mind could be more faster to find a especific voucher without searching in all the papers that we have.
## Purpose
  This project is based on a paper problem where the records that are carried out on paper, it is very easy to lose these records or fill them in an erroneous way, so create a web page where the vouchers are registered and accommodate a simple form and by date where it will maintain an order and better management of internal control and of the borrowed objects.
## Scope
  The control of Voucher is a web application that helps to have a better organization when creating vouchers. it will have specifications such as name, registration number, date, loan tools and the room that was provided. Must have this information to be stored in a different area but before being stored. it must be reviewed by the system and the system will be the one that will choose in what area it will stay if in the "voucher area without observations" or in the "voucher area with observations".
  
this web application has to be connected with a database where all the vouchers will be stored, which is localted on a web-server

## Definitions, acronyms, and abbreviations
| Term | Definition |
| ----------- | ----------- |
| Voucher | Document it has to be filled with the name of the person, his/her registration number, and the tools he will borrow |
|  Data Base  | it is the place where all the document voucher ended are gonna storaged here  |
|  ISC  | identification school card  |


## References
  IEEE SRS PDF 
  
## Overview
 #### Product Perpective
  This system will consist in two part one of them is the web application where all the vouchers that we make are storage and the other   is where all the voucher gonna storage and that it's located into a database.
  
  the web application has to have a different areas where it stored the end or process voucher, the vouncher has to have differents field where they/we has to be filled with all the borrow tools that the customers gonna ask, then voucher gone to the first field that is voucher in progress that storage all it then of that when the customer back the material we need to mark in the right field that the tools is already back if there is not any problem the voucher goes to the next area and that is "ended voucher without observations" meanwhile it has a observation field in the digital voucher goes to differente area "Voucher with observations" and all it storaged into a database server 
 #### Product Functions
  the web application .- has to get the registers from the client.
  
  the data base.- has to have all the ended vouchers.
 #### User Characteristics
  in this part we'll have some actor that are involucrate in this web application.
  
| actors | description |
| ----------- | ----------- |
| customer | it's the person who gonna ask for the materials |
|  Employee  | the employee it's the person who gonna filled the digital voucher with all the record from the customer  |
| Administrator | person who administrate the software and care thet everything is okay with all the functions and bring more material |
| Secondary actors | description |
| Supplier | it is the person who bring all the new materials(Tools) to the place |

 #### Constraints
  one of the constraints that I see is we have three windows and only one computer in it, so this could be the main
  barely the old computer that we have could be also a problem, when we are filling the data.
  all the tools doesn't have a number registration for know how much we have in the inventory.
 #### Assumptions and dependencies
| Assumptions(AS) and dependencies(DE) | description |
| ----------- | ----------- |
| AS.-1 | only one employee use the software per machine |
| AS.-2 | just a client it will be attended |
| DE.-1 | internet connection |
| DE.-2 | bad performance of the computer and end the system |
 #### Apportioning of requirements

## Specific Requirements 
 #### User Interfaces
  in the moment they or we use for the first time we have our web application where it has different sections but first at all we have to choose the button to create a new digital voucher then the employee he/she gather the information from the customer that everything he/she wants and pulled into the digital voucher. 
 #### Hardware Interfaces
  neither of the web application and the database server have any physical hardware both of them are through the internet and does need some hardware
 #### Software Interfaces
  the web application has to be opened with a some web browser to be activated
 #### Communications Interfaces

## Functional requirements
here we describe some scenarios using use cases

use cases: installation

| use cases  | installation |
| ---------- | --------------- |
| actor(s) | administrator |
| Pre-conditional | the Web application is already ended |
| 1.- | the administrator go at the place to turn on the computer |
| 2.- | after it is turn on it start passing the web application document |
| 3.- | check the application is working  |
| 4.- | turn off the computer or whether let the employee start using it  |

![Capture](https://user-images.githubusercontent.com/43121456/57473722-b9fe2680-724d-11e9-9733-0dab3e61def7.PNG)

use cases: asking for tools

| use cases  | borrow of tools |
| ---------- | --------------- |
| actor(s) | Customer and employee |
| Pre-conditional | the Web application is already opened |
| 1.- | the customer goes to the place asking for tools  |
| 2.- | the employee open a new voucher and start filling it |
| 3.- | the employee start giving the tools to the customer |
| 4.- | the customer let his ISC |
| 5.- | the customer it goes |
| 6.- | the employee keep that document and the ISC |

use cases: returning the tools

| use cases | returning the tools without observations |
| ----------- | ----------- |
| Actor(s) | customer and employee |
| pre-conditional | the customer already finish using the tools |
| 1.- | the customer goes for the place he/she asked for tools |
| 2.- | the employee receives the tools and start filled the end field into the digital voucher |
| 3.- | the customer it goes  |
| Alternative | Description |
| line 2 | the tools has a damage when it is returned the voucher gone a different area called "voucher with observations" and it'll call the administrator|


## Appendixes 
  ### Elicitation process 
  at 10:49 a.m. with Juan Guillen and Jesus, they told me about a web application that they do depending on the control of vouchers and they are digital, in which they believe, they are sent to an area in which they remain active until they return tools provided after the delivery is verified if the borrowed tools are in condition which were loaned
me- So, they want vouchers to have a section to check the tools delivered.

they-yes, we also thought that at the end of the voucher if you have in the observations section, you send them to two respective areas "Vales with observations" and "Vales without observations" and keep them in a database and stay there.

Me-and if the vouchers have observations?

they- send us to speak to us and the voucher is saved in the "vouchers with observation" section

Me-then in the area of "Vouchers in process" can be modified to request more material?

they-yes, the students ask for things after having asked.

me- and leave something to take the material?

they- yes,they leave his/her ISC 

me- it has his own inventory storage?

they-we had not thought about it but it you could di that we like to put that in the application

me-how often do you send a message for new material?

they- not much often, just when isn't material

me- and that's all?

they- yes that's all.



