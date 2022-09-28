
![Typing SVG](https://readme-typing-svg.herokuapp.com?color=%2336BCF7&lines=Cinema-App)
## Project description:
>the project was created using Spring and Hibernate technologies. User authentication is implemented (by default) and an administrator can be added if necessary. The user has a basket to which he adds session tickets. To buy tickets that are in the shopping cart, the user sends a post request to the link .../orders/complete
## Project structure:
> The project has an N-Tier Architecture
> * DAO - data access objects - all the work with the database takes place at this stage(CRUD methods)
> * Service - all business logic takes place at the service level
> * Controller - information display
> * DTO - objects used to transfer data from the server to the user and vice versa
## Features:
> * Authentication like User(login\register)
> * Log in / Log out
> * Authorization like user(by default) and admin
> * User has the opportunity to purchase tickets for a movie session
> * Admin has the ability to create/delete new session, new movie
## Technologies:
> * Spring-web
> * Spring-Security
> * Hibernate
> * Java 11
> * Tomcat
> * MySQL
## Instructions for launching the project:
> 1. Fork my repository
> 2. git clone \<your link>
> 3. Edit resources/db.properties - set the necessary parameters
> ```
> db.driver=YOUR_DRIVER
> db.url=YOUR_DATABASE_URL 
> db.user=YOUR_USERNAME 
> db.password=YOUR_PASSWORD
> ```
> 4. Install [Tomcat](https://tomcat.apache.org/download-90.cgi)
> 5. Add Tomcat server to configuration
> 6. Run project
<div id="header" align="center">
  <img src="https://media.giphy.com/media/M9gbBd9nbDrOTu1Mqx/giphy.gif" width="100"/>
</div>
