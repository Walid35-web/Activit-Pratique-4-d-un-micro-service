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
![Screenshot 2023-05-14 174728](https://github.com/Walid35-web/Activit-Pratique-4-d-un-micro-service/assets/85175578/70b3046d-1039-4aff-9fc3-3d5a4ac5b728)
the list of bankaccounts:
![Screenshot 2023-05-14 174849](https://github.com/Walid35-web/Activit-Pratique-4-d-un-micro-service/assets/85175578/e0a5bd18-476f-4448-900b-fab94726dddd)
Consult an account using an id:
![Screenshot 2023-05-14 171822](https://github.com/Walid35-web/Activit-Pratique-4-d-un-micro-service/assets/85175578/f0a4bde6-bae6-4b14-804d-24acb4eda54e)
The restful Web Service communicates with the outside world via a rest API:
The Test with Postman wearing the Id:
![Screenshot 2023-05-14 173751](https://github.com/Walid35-web/Activit-Pratique-4-d-un-micro-service/assets/85175578/1ab90b91-2ed5-41f5-88c5-5fd8186108b5)
Generate and test the Swagger documentation:
![Screenshot 2023-05-14 174515](https://github.com/Walid35-web/Activit-Pratique-4-d-un-micro-service/assets/85175578/3ae1fce8-7832-47ae-80a6-6ff3ad9b7639)
the documentation of rest API:
![Screenshot 2023-05-14 174928](https://github.com/Walid35-web/Activit-Pratique-4-d-un-micro-service/assets/85175578/c89affae-89ea-4730-9178-0650ce294c09)
Test an account with an id:
![Screenshot 2023-05-14 174447](https://github.com/Walid35-web/Activit-Pratique-4-d-un-micro-service/assets/85175578/4e31b662-4f62-4184-bea5-344e0e0c9a5b)
Create an account using post:
![Screenshot 2023-05-14 182047](https://github.com/Walid35-web/Activit-Pratique-4-d-un-micro-service/assets/85175578/1ec444ee-bfe8-46cf-97a0-18ee59a00435)
the account is well created:
![Screenshot 2023-05-14 182104](https://github.com/Walid35-web/Activit-Pratique-4-d-un-micro-service/assets/85175578/68dcba11-4013-4528-84eb-ffea36875d76)
Test the documentation with postman:
![Screenshot 2023-05-14 173722](https://github.com/Walid35-web/Activit-Pratique-4-d-un-micro-service/assets/85175578/9c9ec3a4-c1fd-4798-859a-a1f2ffaea71a)
expose a Restful API using Spring Data Rest by exploiting projections:
![Screenshot 2023-05-14 174849](https://github.com/Walid35-web/Activit-Pratique-4-d-un-micro-service/assets/85175578/1f816284-072a-475a-8b85-35523746866a)
Search for all accounts that have a savings account type:
![Screenshot 2023-05-14 175038](https://github.com/Walid35-web/Activit-Pratique-4-d-un-micro-service/assets/85175578/616f3511-1d6e-4ee8-af56-37c260ba3146)
Create DTOs and Mappers:
![Screenshot 2023-05-14 182047](https://github.com/Walid35-web/Activit-Pratique-4-d-un-micro-service/assets/85175578/17261007-0cec-4cc2-9b32-43f3190ab040)
Create a GraphQL Web service for this microservice:
Account list using ID, balance, currency and query to retrieve a list of accounts:
![Screenshot 2023-05-14 205430](https://github.com/Walid35-web/Activit-Pratique-4-d-un-micro-service/assets/85175578/49b95ff4-2733-428b-a061-4a2feff7f427)
a query to retrieve an account knowing that the Id:
![Screenshot 2023-05-14 205818](https://github.com/Walid35-web/Activit-Pratique-4-d-un-micro-service/assets/85175578/5237b5da-c739-440c-9184-67245d80c649)
Exception handeler:
![Screenshot 2023-05-14 211700](https://github.com/Walid35-web/Activit-Pratique-4-d-un-micro-service/assets/85175578/6ff5c082-86bf-418d-8bb7-9888a5b6ad15)
Add an account using the mutation :
![Screenshot 2023-05-14 212109](https://github.com/Walid35-web/Activit-Pratique-4-d-un-micro-service/assets/85175578/fdd9ee29-6dce-4451-86d2-c0426f21cbcb)
Update the account using the login :
![Screenshot 2023-05-14 213038](https://github.com/Walid35-web/Activit-Pratique-4-d-un-micro-service/assets/85175578/81a72d44-3edd-4d11-be90-52334e3744bd)
Delete the account:
![Screenshot 2023-05-14 213229](https://github.com/Walid35-web/Activit-Pratique-4-d-un-micro-service/assets/85175578/c1029c6f-d158-43d0-a8f3-b5b2bc412871)
the Database :
![Screenshot 2023-05-14 213848](https://github.com/Walid35-web/Activit-Pratique-4-d-un-micro-service/assets/85175578/3edb9863-f15a-42d5-815a-37120d1b3e87)
Search by customer name :
![Screenshot 2023-05-14 214019](https://github.com/Walid35-web/Activit-Pratique-4-d-un-micro-service/assets/85175578/733c37a4-7de7-472b-974e-47ce840be1fc)




