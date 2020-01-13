# 301-practice-2
# 1- In a Handlebars template, what does {{city}} refer to?
A handlebars expression is a {{, some contents, followed by a }}. When the template is executed, these expressions are replaced with values from an input object.
# 2- Explain how the following code in a Node-express server is triggered to run, and what it's output is
server.get('/list', (request, response) => {
   let animals = ['Cat','Dog','Sheep'];
   response.send(200).json(animals);
});
it runs when you type the route /list in the browser and the output will be animals as json formatt
# 3- Write a Constructor function that can create an instance of a person, with a name and an age, given 2 arguments
function People(name,age){
    this.name=name,
    this.age=age
}
let person = new People(dania,27);
console.log(person);