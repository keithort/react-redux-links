### React and AJAX

#### Basic Concepts

- **AJAX Requests in React: How and Where to Fetch Data**  
  https://daveceddia.com/ajax-requests-in-react/  
  An overview of where AJAX requests fit into React usage.
  
- **How to make AJAX requests in React?**  
  https://medium.com/@baphemot/how-to-make-ajax-requests-in-react-a6a52bb5a8b1  
  A helpful introduction to making AJAX requests, including libraries to use, where to run requests, and a couple examples of handling "loading..." status.
  
- **Understanding React: data hydration / initialization**  
  https://medium.com/@baphemot/understanding-reactjs-data-hydration-initialization-bacbb790c7cb  
  Describes several possible approaches to loading data from a server at app startup, including API calls and ways to embed data into the page.
  
- **Where to fetch Data: componentWillMount vs componentDidMount**  
  https://daveceddia.com/where-fetch-data-componentwillmount-vs-componentdidmount/  
  A quick comparison of when these two lifecycle methods are called, and why AJAX calls should generally be done in `componentDidMount`
  
- **How to fetch data in React**  
  https://www.robinwieruch.de/react-fetching-data/  
  An excellent look at several key aspects of fetching in data in React apps, including what components should containg the fetching and display logic, what lifecycle methods to use for API calls, and how to abstract out the fetching process into its own component.

- **React AJAX Best Practices**  
  https://www.javascriptstuff.com/react-ajax-best-practices  
  Covers four ways to approach managing queries and data fetching.

- **AJAX/HTTP Library Comparison**  
  https://www.javascriptstuff.com/ajax-libraries  
  A useful overview of the most popular AJAX libraries, including platform support and feature comparisons.

- **3 Libraries and 3 Ways to handle AJAX in React Apps**  
  https://appendto.com/2017/01/3-libraries-and-3-ways-to-handle-ajax-in-react-apps/  
  Demonstrates three approaches to structuring AJAX calls (root component, containers, and via Redux middleware), and lists three of the most popular AJAX libraries.
  
- **How to make AJAX API calls in React**  
  https://www.techiediaries.com/react-ajax/  
  Looks at common libraries that are used for making AJAX calls in React apps, discusses which lifecycle methods to use for starting AJAX calls, and gives examples of using `fetch` to make AJAX calls.
  

#### Request Implementation Examples

- **Rendering Backend Requests with React**  
  https://blog.boldlisting.com/rendering-backend-requests-with-react-7e493103c2b6  
  Describes a pattern for dealing with components that depend on loading data from a backend
  
- **Build a React + Flux App with User Authentication**  
  https://scotch.io/tutorials/build-a-react-flux-app-with-user-authentication  
  Builds a React app that calls a remote API and authenticates users.  Uses a specific auth provider and basic Flux implementation, but the concepts are widely applicable.
  
- **Handling AJAX In Your React Application with Agility**  
  https://hackernoon.com/handling-ajax-in-your-react-application-with-agility-413f1f21fc70  
  Describes three approaches to fetching data in a React app: within a React component, using the Relay GraphQL library, and using Redux middleware
  
- **You don't need a fancy framework to use GraphQL with React**  
  https://edgecoders.com/you-dont-need-a-fancy-framework-to-use-graphql-with-react-b47b436626fb  
  A detailed explanation of how to construct GraphQL queries in a client and load the data into React components, without using any complicated libraries.
  

#### Handling Request Status with State

- **React-Redux issue #210: "dispatching in componentWillMount?"**  
  https://github.com/reactjs/react-redux/issues/210#issuecomment-244774674  
  Some valuable extended discussion about how managing requests and data really involves several distinct possible states.

- **"Slaying a UI Antipattern" comparisons**  
  http://blog.jenkster.com/2016/06/how-elm-slays-a-ui-antipattern.html  
  https://medium.com/javascript-inside/slaying-a-ui-antipattern-in-fantasyland-907cbc322d2a  
  https://medium.com/@gcanti/slaying-a-ui-antipattern-with-flow-5eed0cfb627b  
  https://medium.com/@marsbergen/nice-pattern-for-redux-state-b8641b6ff9d1 
  https://medium.com/javascript-inside/slaying-a-ui-antipattern-in-react-64a3b98242c  
  Articles by different authors that demonstrate how to handle the common "loading/no data/data" issue with various static typing approaches and FP principles.
  
- **A Better Way To Handle Loading State In Redux**  
  http://nikolay.rocks/2017-06-18-better-redux-loading  
  Discusses several ways to store "loading/success/failure" state, and tradeoffs of the approaches.  Talks about Redux, but applies to React as well.