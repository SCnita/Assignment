#Assignment

To run the project:-
1.Download the project.
2.Open the project in Spring Tool Suite.
3. Create vedantu database.
4.Provide path in application.yml.
5.Run the project.
4.Perform the testing using Postman.


API endpoints:-
POST : /api/account/add -> To add account.
POST : /api/inventory/add -> To add item in inventory.
GET : /api/inventory/getall -> To get all items in inventory.
GET : /api/inventory/get/{id} -> To get the details of item having id.
POST : /api/order/add ->  To place order.
GET : /api/order/get/{id} -> To get the details of the order having id.




Input json for account:-

{"email":"abc@abc.com"}




Input json for inventory:-

{
  "itemName": "samsung m50",
  "brandName": "Samsung",
  "description": "samsung phone m50 mobile phone",
  "actPrice": 15000,
  "disPrice": 12000,
  "sellerInfo": "ABC retail bangaluru",
  "totalRatingSum": 0,
  "totalNoRating": 0,
  "unitsInStock": 1000,
  "totalUnitsSold": 0,
  "returnDuration": 15,
  "imgLink1": "",
  "imgLink2": "",
  "imgLink3": "",
  "imgLink4": "",
  "outOfStock": false,
  "returnable": true
}







Input json for the order placement:-


{
	"userEmail":"abc@abc.com",
	"items":[{"itemId":1,"quantity":1}],
	"modeOfPayment":0,
	"pincode":799046,
	"addressCountry":"India",
	"addressState":"Tripura",
	"addressDistrict":"Agartala",
	"addressLandmark":"Aryabhatta hostel",
	"addressFirstLine":"Room 2014",
	"addressSecondLine":"Aryabhatta hostel",
	"addressThirdLine":"Nit agartala"
}
