# Docter-App
Making a Docter-App  with java-Spring-Boot
Creating a Hospital system using java spring boot 
Where We are having Doctor and Patient as seperate Entitiy.
Patient can make appoinments
Doctor can see his/her appoinments with patients
we can verify both doctor and patient by using Authentication
App Has following properties as Entities
* Doctor
* Patient
* Appointments
* Admin
* Authentication

  #### our project is having following endpoints
   * addDoctor 
   * getAllDoctors
   * getAllPatients
   * appointment
   * appointment/cancel
   * getAllAppointments

## Frameworks and languages used
* Spring
* java
* maven
* Hibernate-validation
* Regex for validating patterns
* H2 Database

## Data Flow
 * Controller<br>
         <p>- It is just containg Api endPoint and logic for<br> 
           what should this api do.</p>
* Services<br>
        <p>- It has actual logic(business logic) for method.<br> 
          It is also called Model.</p>
       
 * Repository<br>
           - It is having data source
 * Model
      ```
       <P> It has the actual model of<br>
                 - Doctor<br>
                 - Patient<br>
                 - Appointment<br>
                 - Admin<br>
                 - Authentication<br>
   what properties they have as Entity.</P>
    ```
                 

 ## Data Structure
   * Here we are using List(ArrayList) datastructure to store and manipulate data.
