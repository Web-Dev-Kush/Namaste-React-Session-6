Chapter 06 - Exploring the world
Theory Assignment:
What is Microservice?
Microservices are an architectural and organizational approach to software development where software is composed of small independent services that communicate over well-defined APIs. These services are owned by small, self-contained teams.
What is Monolith architecture?
A monolithic architecture is a singular, large computing network with one code base that couples all of the business concerns together. To make a change to this sort of application requires updating the entire stack by accessing the code base and building and deploying an updated version of the service-side interface.
What is the difference between `Monolith and Microservice?
A monolithic application is built as a single unified unit while a microservices architecture is a collection of smaller, independently deployable services.
Why do we need a useEffect Hook?
The useEffect Hook allows you to perform side effects in your components.
Some examples of side effects are: fetching data, directly updating the DOM, and timers.
useEffect accepts two arguments. The second argument is optional.
useEffect(<function>, <dependency>)
What is Optional Chaining?
The optional chaining (?.) operator accesses an object's property or calls a function. If the object accessed or function called using this operator is undefined or null, the expression short circuits and evaluates to undefined instead of throwing an error.
What is Shimmer UI?
A shimmer UI resembles the page's actual UI, so users will understand how quickly the web or mobile app will load even before the content has shown up. It gives people an idea of what's about to come and what's happening (it's currently loading) when a page full of content/data takes more than 3 - 5 seconds to load.
What is the difference between JS expression and JS statement?
An expression is a block of code that evaluates to a value. A statement is any block of code that is performing some action. The distinction between an expression and a statement is important because an expression is a subset of a statement.
What is Conditional Rendering? explain with a code example.
Conditional rendering in React works the same way conditions work in JavaScript. Use JavaScript operators like if or the conditional operator to create elements representing the current state, and let React update the UI to match them.
function Greeting(props) {
  const isLoggedIn = props.isLoggedIn;
  if (isLoggedIn) {    return <UserGreeting />;  }
  return <GuestGreeting />;}
const root = ReactDOM.createRoot(document.getElementById('root')); 
// Try changing to isLoggedIn={true}:
root.render(<Greeting isLoggedIn={false} />);
What is CORS?
In ReactJS, Cross-Origin Resource Sharing (CORS) refers to the method that allows you to make requests to the server deployed at a different domain. As a reference, if the frontend and backend are at two different domains, we need CORS there.
What is async and await?
Async/Await
Async await is syntactic sugar for promises. Making code looks like executed synchronously.
Async await does not have states. Async functions return a promise. This promise state can be either resolved or rejected.
Await suspends the called function execution until the promise returns a result for that execution. If there are other functions called after await, these executions wait until the promise finishes.
Error handling can be done with a try-catch block.
Async/Await makes reading the promises flow much easier. Understanding the functionality is also very easy compared to promises.
Debugging is much easier with async/await.
Await can be used for a single promise or promise.all().


What is the use of const json = await data.json(); in getRestaurants()?


Coding Assignment:
Play with the useEffect Hook to see when it is called? (before or after render)
Play with the dependency array in useEffect Hook.
Play with the developer console by putting a debugger in render and useEffect.
Call an actual API call.
Handle Error in your API call.
Build Shimmer UI when data is not loaded.
Render your UI with actual API data.
Make Search functionality work.
Make a Login Logout button that toggles with a state.
References:
Akshay Saini Code Link
