# 301-practice-2

## 1. In a Handlebars template, what does {{city}} refer to?

its A handlebars expression and refers to the template input object value.

## 2. Explain how the following code in a Node-express server is triggered to run, and what it's output is

 server.get('/list', (request, response) => {
   let animals = ['Cat','Dog','Sheep'];
   response.send(200).json(animals);
});

 **solution:**

 *we should replace (response.send(200)) with (response.status(200))*
 *then the output will be the array animals ['Cat','Dog','Sheep']*


## 3. Write a Constructor function that can create an instance of a person, with a name and an age, given 2 arguments

Your code goes here...

function Person(name,age){
    this.name=name;
    this.age=age;
};