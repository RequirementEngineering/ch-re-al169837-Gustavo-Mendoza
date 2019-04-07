## Introduction 
  The place where I work we have a voucher system also we want to improve reducing the paper to have a better control and managment. It make a inventory where all the voucher storage into a DataBase with that in mind could be more faster to find a especific voucher, without searching in all the papers that we have.
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
 #### Product Functions
  the web application .- has to get the registers from the client.
  
  the data base.- has to have all the ended vouchers.
 #### User Characteristics
  in this part we'll have some actor that are involucrate in this software.
  
| actors | description |
| ----------- | ----------- |
| Client | it's the person who gonna ask for the materials |
|  Employee  | the employee it's the person who gonna filled the digital voucher with all the record from the customer  |
| Administrator | person who administrate the software and care thet everything is okay with all the functions |

 #### Constraints
  one of the constraints that I see is we have three windows and only one computer in it, so this could be the main
  barely the old computer that we have could be also a problem, when we are filling the data.
  all the tools doesn't have a number registration for know how much we have in the inventory also the internet we need to make more       large. 
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
  in the moment they or we use for the first time we have our web application where it has different sections but first at all we have to choose the button to create a new digital voucher then the employee he/she gather the information from the customer that everything he/she wants and pulled into the digital voucher 
 #### Hardware Interfaces
  neither of the web application and the datbase server have any physical hardware both of them are through the internet and does need some hardware
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

| use cases | returning the tools |
| ----------- | ----------- |
| Actor(s) | customer and employee |
| pre-conditional | the customer already finish using the tools |
| 1.- | the customer goes for the place he/she asked for tools |
| 2.- | the employee receives the tools and start filled the end field into the digital voucher |
| 3.- | the employee if everything it's okay returning all the borrow tools the employee return the ISC |
| 4.- | the customer it goes  |ing
