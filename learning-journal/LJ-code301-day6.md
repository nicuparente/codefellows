# LJ Code 301 - Day 3

We went through a lot of terms topics today regarding how the web works and how a users request are handled.

#### **TERMS**
- **WRRC** - Web Request Response Cycle
- **FP** - Functional Programming
- **CRUD** - Create, Read, Update and Update
- **ReST** - Representational State Transfer
- **URL** - Uniform Resource Locator
- **AJAX** - Asynchronous JavaScript And XML
- **JSON** - JavaScript Object Notation
---

##### URL BREAKDOWN
https://www.codefellows.com/blog.html#today?page=2&admin=true
- **protocol**: http://
- **[sub]domain**: www.codefellows.org
- **path**:/blog
- **format**: .html
- **named anchor**: #today
- **parameters**: ?page=2&admin=true


---
### **WRRC**
User -> DNS Lookup -> Request -> Response -> User

### **HTTP Request Object**
- URL
- Method
- Headers

## **JSON**

All keys are covered in double strings

## **AJAX**
```JavaScript
  $.ajax({
    url: 'http://pokeapi.co/api/v2/pokemon/52', //URL
    method: 'GET',                              //REST Method
    success: function(data, message, xhr){      //if call is successful do this
      console.log(data.name);
    }
  });
```


## **SCOPE**
``` JavaScript
  let x = 0; //scoped to the codeblock but can be changed
  const z = 0; //Cannot assign a new value. The value is immutable. You can assign it an object or an array and push values to it.
  var y = 0; // can be changed and is only scoped in functions
```

## **.then()**
``` JavaScript
  $.getJSON("some/url/path").then(
    function(data, message, xhr){ //Run this function if the call was successful
      //do stuff here
      console.log(data);
    },
    function(err){ //Run this function if the call failed
      //do stuff here
      console.log(err);
    }
  );

```
