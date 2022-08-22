------------------------ShopForHome-----------------
### For Product details and admin user details

---To get the products and to login as a admin you need to upload the product.json file 
   and users.json file in your mongodb 

Admin Login
````
{
    "email": "jayashree.dasari2000@gmail.com",
    "password": "123456789"
}
---
{	"role": "admin",  
	"name": "DASARI ",  
	"email": "jayashree.dasari2000@gmail.com",  
	"password": "$2a$10$50Wxg/7Ie4daS7r6ABhIiOi5CVeCFzFSUzrqY6dPugXbB7ir42Gfq",  
	"avatar": {    "public_id": "avatars/isnev9avfjci5kcsvmbh",    
	"url": "https://res.cloudinary.com/dsjbki7ta/image/upload/v1656962080/avatars/isnev9avfjci5kcsvmbh.jpg"  },  
	"createdAt": {    "$date": {      "$numberLong": "1656962081482"    }  },  "__v": 0,  
	"resetPasswordExpire": {    "$date": {      "$numberLong": "1657131594341"    }  },  "resetPasswordToken": "66d5ea5cca757c0aa48d4b2faf5ad19c45636d945446b8cd0b52b41798d16bc9",  	"discount": 12
}

```
User Login

```
{
    "email": "ravi@gmail.com",
    "password": "123456789"
}
```{  "role": "user",  "name": "Dasari Jayashree",  
	"email": "jayashreed.be22@uceou.edu",  
	"password": "$2a$10$rffyC/qAobmoh/Kz5cNPqeBSxd3.ru.duNxiaVDAMBUwSVawIuRc6",  
	"avatar": {    "public_id": "avatars/to1yz8gydjxkqqtkjce8",    
	"url": "https://res.cloudinary.com/dsjbki7ta/image/upload/v1657039863/avatars/to1yz8gydjxkqqtkjce8.png"  },  
	"createdAt": {    "$date": {      "$numberLong": "1657039865380"    }  },  "__v": 0,  
	"resetPasswordExpire": {    "$date": {      "$numberLong": "1657042358955"    }  },  
	"resetPasswordToken": "259c53943be95ba499b14ef70a62256359de7cf1d593029a1d587691daf493a0",  
	"discount": 55
}
---
--now Install dependencies 

navigate to frontend 
-->cd frontend
give---> npm install

open a new terminal 
navigate to backend
cd backend
give---> npm install

To Run the Application

---for server
...cd backend -> npm run dev

---for running client
...cd frontend -> npm start

## client running on  http://localhost:8000/

## server running on port 4000
