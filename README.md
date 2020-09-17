# Drop-Pickup :package:
  
Admin site: https://admin-drop-and-pickup.herokuapp.com/admin

Main site: https://drop-and-pickup.herokuapp.com/login
### Super user credentials (admin site):
- username: admin
- password: admin123

### Clients Users (admin site):
- username: client1@gmail.com
- password: 0000000000B

### Staging Users (main site):

`Note: if you made changes and did not see data, refresh the page. Users are technically on the same table in the database, so if you login in the main site using admin users, you will not get the desired experience.
`

-- email: ahmadsameer@gmail.com 
-- password: ahmadsameer

-- email: mohammadali@gmail.com
-- password: mohammadali

## Create a store:
- To create a store, you have to create a client, then go to users and create a user and assign him/heer a client.
- Logout from super user and login with store credentials and you should see you shipments and other details.




This is the main repo for Team Drop and Pickup.

Team Members:
  - Mahdy Mousa/Hamad

## Main Goal :rocket:
Our idea is to create a platform to be the median in which makes delivery of items between indeviduals easier and more flixable. The delivery process begins when a person signup to the platform and create a DROP order, then he/she will select the person whom recieving this package, the package details, the closest store in which the package will stay until the authorized person pick it up.

## Architecture 
The platform is a web application consist of two parts, the Frontend, and the Backend.
### The Frontend
We are using Angular 8 to create an interactive user interfaces for the platform. We use Typescript to achieve that.

### The Backend
The backend is written in Python using Django as the framework. 
