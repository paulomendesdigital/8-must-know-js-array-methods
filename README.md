# 8 must know js array methods

```javascript
const items = [
	{ name: 'Bike',		price: 100 },
	{ name: 'TV',		price: 100 },
	{ name: 'Album',	price: 100 },
	{ name: 'Book',		price: 100 },
	{ name: 'Phone',	price: 100 },
	{ name: 'Computer',	price: 100 },
	{ name: 'keyboard',	price: 100 },
];


//filter de content by the verification pass
const filteredItems = items.filter((item) => {
	return item.price <= 100;
});


//return a array with the value pass
const itemName = items.map((item) => {
	return item.name;
});


//return the object where the verification is true
const foundItem = items.find((item) => {
	return item.name === 'Bike';
});


//walks at the each objetc
items.foreach((item) => {
	console.log(item.name);
});


//return true or false by the verification
const hasInexpensiveItems = items.some((item) => {
	return item.price <= 100;
});


//return true if some verification is true
const hasInexpensiveItems = items.some((item) => {
	return item.price <= 100;
});


//return true if every verification is true
const hasInexpensiveItems = items.every((item) => {
	return item.price <= 100;
});


//walks by items and sum the each price in currentTotal and the total is store in total variable
const total = items.reduce((currentTotal, item) => {
	return currentTotal + item.price;
}, 0);

const numbers = [2, 2, 3, 4, 5];

//return true if the param (2) is in number
const includesTwo = items.includes(2);
```
