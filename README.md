# TrafficLive

- - - - - - - - - 

## CO227-Project- Database for traffic violations mobile app with QR Scanner,Number plate recognition and data retrieving


Project Colloborators: 

* [Ishani Maduwanthi](https://github.com/ishaniMadhuwanthi)
* [Roshani Dilhara](https://github.com/RoshaniDilhara)
* [Imalsha Dinuwanthi](https://github.com/Imalshadinu)

---------------------------------------------------------------------------------


## Project Description

This project is under the category of Database for traffic violations. Our targeted end users are,
  - Police officers
  + Authorized persons in traffic violation controlling 

There are so many traffic violations and accidents happend in the road. Police officers record those in their books. Actually they are hand written recordings. So they are less in accuracy. And also when there is an accident or any rode rule violation, police officers can't view other related violations done by the particular vehicle or driver.  

So that, our project owner, the police officers required a mobile application to enter traffic data more efficient and securely rather than entering details manually.

### Solution

It is a mobile app, developed by using Android Studio with Java . It includes QR Scanner and Number Plate Recognition. 
We develped a mobile application. 

  **Fontend**  : Android Studio with Java
  
  **Database** : Firebase
  
Following are the functionalities that we have used in the application.
* **QR Scanner** to capture driving license details (Here we assumed that there is a QR code included in newly created driving licenses)
    * Driver name
    * Driver address
    * License number
    * NIC

When QR Code in the license is scanned, all the details are updated in the database.

* **Number Plate Recognition** to record vehicle details
    * Vehicle number
    * Registered Date

The app will open mobile camera from a button click and can take vehicle number plate photo and recognition its details and realtime update the database.

* **Data retrieving**

We have used Firebase Database. All the details taken from QR code scaning and vehicle number plate recogintion are updated in the database. Therefore, by entering **NIC number** of the driver, the police officer can retrieve data and find his previous traffic violations. 


## How to run the Application

1. Clone the repository.
2. Open the folder with Android studio. (prefered language is java)
3. Setup android studio setting to run a mobile application.
4. Run the code. 
5. The apllication will open up in your andorid phone. 

## Dependencies
