# day-3-task
FOR IN LOOP 
var person = {
   fname: "Nick",
   lname: "Jonas",
   age: 26
}; 
for (let x in person) {
   console.log(x + ": "+ person[x])
}
‍FOR LOOP
var numbers = [ 10, 20, 30, 40, 50] 
for (var i=0; i < numbers.length; i++) {
   console.log(numbers[i])
}
FOR EACH 
var names = ["jerry", "tom", "pluto", "micky", "mini"];
names.forEach(function1);
function function1(currentValue, index) {
   console.log("Index in array is: "+index + " ::  Value is: "+currentValue);
}



RESUME DATA ON JSON

{
  "basics": {
    "name": "jayuriyan.p",
    "label": "",
    "picture": "",
    "email": "jayasuriyanponnusamy@gmail.com",
    "phone": "9626403292.",
    "degree": "B.E",
    "website": "Your website URL",
    "summary": "A perfect",
    "location": {
      "address": "south street trichy",
      "postalCode": "62109",
      "city": "trichy",
      "countryCode": "indian)",
      "region": "hindu)"
    },
    "profiles": [
      {
        "network": "google",
        "username": "jayasuriyan",
        "url": "A URL to your user profile page
      ]
    }
  ],
  "education": [
    {
      "institution": "dsme ",
      "area": "perambalur",
      "studyType": "",
      "startDate": "02/04/2018",
      "endDate": "19/04/2022",
      "gpa": "7.09",
      "courses": [
        "B.E mech"
      ]
    }
  ],
