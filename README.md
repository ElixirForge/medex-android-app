<div align="center">
<img src="readmeResources/Medex.png" alt="Medex" width="225">
     <h3 align="center">The Medex Software Suite</h3>
     <img src="https://img.shields.io/static/v1?label=&message=Java&color=important&logo=java"> <img src="https://img.shields.io/static/v1?label=&message=Jersey&color=important&logo=Java"> <img src="https://img.shields.io/static/v1?label=&message=AWS&color=282c3c&logo=amazon"> <img src="https://img.shields.io/static/v1?label=&message=MySQL&color=white&logo=mySQL"> <img src="https://img.shields.io/static/v1?label=&message=Android Studio&color=40dc84&logo=android&logoColor=white">  
<br>
<a href="https://www.github.com/ElixirForge/medex-shopping-microservice"><img src="https://img.shields.io/static/v1?label=&message=medex-shopping-microservice&color=000000&logo=github"></a> <a href="https://www.github.com/ElixirForge/medex-pharmacy-microservice"><img src="https://img.shields.io/static/v1?label=&message=medex-pharmacy-microservice&color=000000&logo=github"></a> <a href="https://www.github.com/ElixirForge/medex-personnel-microservice"><img src="https://img.shields.io/static/v1?label=&message=medex-personnel-microservice&color=000000&logo=github"></a> <a href="https://www.github.com/ElixirForge/medex-doctor-microservice"><img src="https://img.shields.io/static/v1?label=&message=medex-doctor-microservice&color=000000&logo=github"></a>  
</div> 
<hr>
<div align="center">
    <img src="readmeResources/Android.png" alt="android" width="150">
  <h3 align="center">Android Mobile App</h3>
</div>

<hr>
<div align="center">
  <h4>This repository is a stub. Code will be added.</h4>
</div>
<hr>

## :raising_hand: Attributions
Pharmacy icon made by <a href="https://www.flaticon.com/authors/catkuro" title="catkuro">catkuro</a> from <a href="https://www.flaticon.com/" title="Flaticon">www.flaticon.com</a>  
Warehouse icon made by <a href="https://www.flaticon.com/authors/nhor-phai" title="Nhor Phai">Nhor Phai</a> from <a href="https://www.flaticon.com/" title="Flaticon">www.flaticon.com</a>  
All other icons made by <a href="https://www.freepik.com" title="Freepik">Freepik</a> from <a href="https://www.flaticon.com/" title="Flaticon">www.flaticon.com</a>  


## :hospital: Shared With the Microservice Repositories - About Medex
A group project full stack application that utilizes Android Studio, Java Jersey, MySQL, and AWS.  
The goal of the project was to acquire more experience in utilizing HTTP requests & RESTful APIs, microservice architecture, and high-availability AWS deployments.  
<br>
The premise behind Medex is to connect doctors, patients, couriers and pharmacies with one another such that patients can use e-prescriptions provided by their doctors to order pharmaceuticals, which are delivered from the pharmacies to the patient through a courier.  
<br>
More precisely, here are the requirements of Medex:
- [x] <b>Register and Login</b>  
          Patients, doctors, personnel and pharmacies can register and login to Medex, giving them access to their dedicated UX on the Android app  
- [x] <b>Patients can interact with pharmacy and medicine catalogs</b>  
          Patients can view the catalog of pharmacies, the medicine in each pharmacy, and add medicine to cart 
- [x] <b>Patients can pay for their carts</b>  
          Patients can use their "wallets" to pay for the contents of their carts, automatically consuming their prescriptions and funds in the process
- [x] <b>Patients can view their prescriptions</b>  
          Patients are able to check their prescriptions and how many times each prescription can be used
- [x] <b>Patients can interact with their orders</b>  
          Patients can view their orders and the order items along with modifying the items, and refunding their orders 
- [x] <b>Personnel can assign an order to themselves</b>  
          Personnel can choose to assign an order to themselves; the orders are assigned on a first-come-first-serve (FCFS)
- [x] <b>Personnel can utilize maps to find the location of their assigned order</b>  
          Personnel would have access to maps, displaying the location they should deliver to
- [x] <b>Personnel can mark orders as done</b>  
          Once a delivery is made, the personnel can mark their current order as done
- [x] <b>Pharmacies can add medicine to the global medicine database</b>  
          Pharmacies can add newly acquired medicine in the market that can be used by all pharmacies 
- [x] <b>Pharmacies can view and manage their stock</b>  
          Pharmacies have their own stock which is a subset of the global medicine database which they can modify in terms of quantity, and pricing
- [x] <b>Doctors can view and manage their patients</b>  
          Every doctor has a list of patients which is a subset of the list of patients using Medex, the doctors can assign and unassign patients to themselves
- [x] <b>Doctors can view and manage the prescriptions of their patients</b>  
          Doctors can assign, modify and revoke the prescriptions of patients  
- [x] <b>Doctors can view the global medicine database</b>  
          The doctors are able to view the medicine available and assign them to the patients accordingly  

## :flight_departure: How To Run
1. Install [Android Studio](https://developer.android.com/studio) on your computer  
2. In Android Studio, go to File --> New --> Project from Version Control --> Configure your GitHub account --> URL: `https://github.com/ElixirForge/medex-android-app.git`
3. If you don't have an Android virtual device, go to AVD manager (Top right corner) and create a `Nexus 9 API 29`
4. Change the the base URL everywhere to your desired base URL (Perhaps the microservice is hosted on AWS for example). If you are hosting the microservice(s) locally then use the provided `http://10.0.2.2:8080/`. (Yes, I should have made a global baseURL variable.)
5. Run, and orient the virtual device to landscape mode

## :question: How To Use
1. Run any of the desired microservices (The repositories can be seen on top of the readme file; instructions are included)
2. Populate the database of the microservice you would like to test (Credentials, etc)
3. Login using the UX!

<div align="center">
<img src="readmeResources/Login UX.png" alt="Login" width="500">
<img src="readmeResources/Shopping UX.png" alt="Shopping" width="500">
<img src="readmeResources/Pharmacy UX.png" alt="Pharmacy" width="500">
<img src="readmeResources/Personnel UX.png" alt="Personnel" width="500">
<img src="readmeResources/Doctor UX.png" alt="Doctor" width="500">
</div>
