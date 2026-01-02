## StudentData_API-TestCases

Get All Data By 
http://localhost:8080/students

Get data using ID 
http://localhost:8080/students/ID

Post Data 
http://localhost:8080/students
{   
    "course":"CSE",
    "email":"raunakranjann@gmail.com",
    "phno":"1234567890",
    "name":"Raunak Ranjan",
    "roll":"22CS03"
}

Post Multiple Data
http://localhost:8080/students/multiple

[{   
    "course":"CSE",
    "email":"saurabh@gmail.com",
    "phno":"1234567890",
    "name":"Saurabh bist",
    "roll":"22CS07"
},{   
    "course":"CSE",
    "email":"dev@gmail.com",
    "phno":"1234567890",
    "name":"Dev Soni",
    "roll":"22CS11"
}]



Update Data using ID
http://localhost:8080/students/ID

{   
    "course":"CSE",
    "email":"xyz@gmail.com",
    "phno":"00112901",
    "name":"Raunak Ranjan",
    "roll":"22CS007"
}

Delete Data using ID 
http://localhost:8080/students/ID
