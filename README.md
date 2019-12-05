#Assignment

To run the project:- <br />
1.Download the project. <br />
2.Open the project in Spring Tool Suite. <br />
3. Create vedantu database. <br />
4.Provide path in application.yml. <br />
5.Run the project. <br />
4.Perform the testing using Postman. <br />


API endpoints:- <br />
POST : /api/account/add -> To add account. <br />
POST : /api/inventory/add -> To add item in inventory. <br />
GET : /api/inventory/getall -> To get all items in inventory. <br />
GET : /api/inventory/get/{id} -> To get the details of item having id. <br />
POST : /api/order/add ->  To place order. <br />
GET : /api/order/get/{id} -> To get the details of the order having id. <br />




Input json for account:- <br />

{"email":"abc@abc.com"} <br />




Input json for inventory:- <br />

{ <br />
  "itemName": "samsung m50", <br />
  "brandName": "Samsung", <br />
  "description": "samsung phone m50 mobile phone", <br />
  "actPrice": 15000, <br />
  "disPrice": 12000, <br />
  "sellerInfo": "ABC retail bangaluru", <br />
  "totalRatingSum": 0, <br />
  "totalNoRating": 0, <br /> <br /> <br />
  "unitsInStock": 1000, <br /> <br />
  "totalUnitsSold": 0, <br />
  "returnDuration": 15, <br />
  "imgLink1": "", <br />
  "imgLink2": "", <br />
  "imgLink3": "", <br />
  "imgLink4": "", <br />
  "outOfStock": false, <br />
  "returnable": true <br />
} <br />







Input json for the order placement:- <br />


{ <br />
	"userEmail":"abc@abc.com", <br />
	"items":[{"itemId":1,"quantity":1}], <br />
	"modeOfPayment":0, <br />
	"pincode":799046, <br />
	"addressCountry":"India", <br />
	"addressState":"Tripura", <br />
	"addressDistrict":"Agartala", <br />
	"addressLandmark":"Aryabhatta hostel", <br />
	"addressFirstLine":"Room 2014", <br />
	"addressSecondLine":"Aryabhatta hostel", <br />
	"addressThirdLine":"Nit agartala" <br />
} <br />
