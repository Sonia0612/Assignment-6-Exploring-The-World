# Episode-6-Exploring the World-
## Theory

Qn1. What is MicroService?

- It is an architectural style which breaks down an application into several services.
- Each services runs it's own processess and communicates through APIs.
- Decomposition by use case - i.e., microservices handle specific actions. 
- For example, Amazon uses a specialized microservice to process shipping orders. 
- https://www.linkedin.com/pulse/react-architecture-microservice-approach-front-end-mischa-rouleaux/


Qn2. WHat is a Monolith Architecture?

- Monolith means composed all in one piece.
- We don't break down down the application here but contain an ordering system, a payment function, and a shipping component in same code.
-  monolithic application describes a single-tiered software application in which the user interface and data access code are combined into a single program from a single platform.
-  A monolithic application is self-contained and independent from other computing applications.

Qn3. Diff btw Monolith and microservice

- ![image]([https://github.com/Sonia0612/Assignment-6-Exploring-The-World/assets/86123814/3a7748dd-bcbc-4fd3-bb36-b8befa9f1c74](https://github.com/Sonia0612/Assignment-6-Exploring-The-World/assets/86123814/3a7748dd-bcbc-4fd3-bb36-b8befa9f1c74))

Qn4. Why do we need useEffect Hook?

- The useEffect Hook allows you to perform side effects in your components.
-  Some examples of side effects are: fetching data, directly updating the DOM, and timers.
-   useEffect accepts two arguments. The second argument is optional.
-    useEffect is a tool that lets us interact with the outside world but not affect the rendering or performance of the component that it's in.
-    basically, we tell ou component needs to do something(eg. fetch data) after rendering.
### useEffect(<function>, <dependency>)

Qn5. WHat is Optional Chaining?
 
- Optional chaining is a process for querying and calling properties, methods, and subscripts on an optional that might currently be nil.
- If the optional contains a value, the property, method, or subscript call succeeds; if the optional is nil , the property, method, or subscript call returns nil .
- The optional chaining (?.) operator accesses an object's property or calls a function.
- If the object accessed or function called using this operator is undefined or null, the expression short circuits and evaluates to undefined instead of throwing an error.
### Example
-const adventurer = {
- name: 'Alice',
- cat: {
-   name: 'Dinah'
- }};
- const dogName = adventurer.dog?.name;
- console.log(dogName);

Qn6. What is Shimmer UI?
 
- Shimmer effect was created by Facebook to indicate a loading status, so instead of using ProgressBar or usual loader use Shimmer for a better design and user interface. 
- When data is being loaded and instead of showing the empty page in UI what we can do is load the page with the actual UI but without data.
- meanwhile, the data gets fetched and the UI can be filled with the data.

Qn7. Diff btw Js expression and statement
 
- An expression is any valid unit of code that resolves to a value.
eg. 10, 10>9
 
- A statement is a unit of code that performs an action
- var a=10;
### conditional statements
- if(loading){
- console.log('true');}
- else{
- console.log('false');}

Qn8. What is Conditional Rendering? Explain with eg.
 
- In React, conditional rendering is the process of displaying different content based on certain conditions or states.
- It allows you to create dynamic user interfaces that can adapt to changes in data and user interactions.
-  3 ways to do conditional rendering
- 1. If Statement  - ### if (isGoal) {return <MadeGoal/>;} return <MissedGoal/>;
- 2. logical && operator - ### {cars.length > 0 && <h2>hi</h2>}
- 3. Ternary operator  -  ### {loading?<Component1/>:<Component2/>}


Qn9. What is CORS?
 
- CORS enables you to access a resource from a different origin. 
- Cross-Origin Resource Sharing (CORS) refers to the method that allows you to make requests to the server deployed at a different domain. 
- is a mechanism to restrict users from accessing shared resources. 
- This is not an error but a security measure to secure users or the website which you are accessing from a potential security breach.

Qn10. What is async and await?
 
- The keyword async before a function makes the function return a promise:
-  async makes a function return a Promise
-  await makes a function wait for a Promise
- async function(){
- let value= await promise;
- }
 
Qn11. What is use of const json=await data.json(); in getrest()?
 
- The data object, returned by the await fetch() , is a generic placeholder for multiple data formats. }); 
- data.json() is a method of the data object that allows a JSON object to be extracted from the response data.
- The method returns a promise, so you have to wait for the JSON: await response.json() 
- json() is asynchronous and returns a Promise object that resolves to a JavaScript object
