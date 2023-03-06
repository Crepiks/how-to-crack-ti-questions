# React Interview Questions & Answers

### Table of Contents

| No.  | Questions                                                                                           | Priority |
|------|-----------------------------------------------------------------------------------------------------|----------|
|      | **Core React**                                                                                      | HIGH     |
| 1    | What is React?                                                                                      | HIGH     |
| 2    | What are the major features of React?                                                               | HIGH     |
| 3    | What is JSX?                                                                                        | HIGH     |
| 3.1  | Is it possible to use react without JSX?                                                            | HIGH     |
| 4    | What is the difference between Element and Component?                                               | HIGH     |
| 5    | How to create components in React?                                                                  | HIGH     |
| 6    | When to use a Class Component over a Function Component?                                            | LOW      |
| 7    | What are Pure Components?                                                                           | MEDIUM   |
| 7.1  | If Pure Component is better from the optimization point of view, why don't we use it by default?(#) | MEDIUM   |
| 8    | What is state in React?                                                                             | HIGH     |
| 9    | What are props in React?                                                                            | HIGH     |
| 10   | What is the difference between state and props?                                                     | HIGH     |
| 11   | Why should we not update the state directly?                                                        | HIGH     |
| 11.1 | Is the state updated synchronously?                                                                 | HIGH     |
| 12   | What is the purpose of callback function as an argument of setState()?                              | MEDIUM   |
| 13   | What is the difference between HTML and React event handling?                                       | LOW      |
| 14   | How to bind methods or event handlers in JSX callbacks?                                             | HIGH     |
| 15   | How to pass a parameter to an event handler or callback?                                            | HIGH     |
| 16   | What are synthetic events in React?                                                                 | HIGH     |
| 17   | What are inline conditional expressions?                                                            | MEDIUM   |
| 18   | What is "key" prop and what is the benefit of using it in arrays of elements?                       | HIGH     |
| 19   | What is the use of refs?                                                                            | HIGH     |
| 20   | How to create refs?                                                                                 | HIGH     |
| 20.1 | Difference between "createRef" and "useRef"(#)                                                      | MEDIUM   |
| 21   | What are forward refs?                                                                              | MEDIUM   |
| 22   | React.memo VS useMemo                                                                               | HIGH     |
| 23   | How do you memoize a component?                                                                     | HIGH     |
| 24   | What is Virtual DOM?                                                                                | HIGH     |
| 25   | How Virtual DOM works?                                                                              | HIGH     |
| 26   | What is the difference between Shadow DOM and Virtual DOM?                                          | HIGH     |
| 27   | What is React Fiber?                                                                                | HIGH     |
| 28   | What is the main goal of React Fiber?                                                               | HIGH     |
| 29   | What are controlled components?                                                                     | MEDIUM   |
| 30   | What are uncontrolled components?                                                                   | MEDIUM   |
| 30.1 | Controlled Uncontrolled VS Uncontrolled inputs.                                                     | MEDIUM   |
| 31   | What is the difference between createElement and cloneElement?                                      | LOW      |
| 32   | What is Lifting State Up in React?                                                                  | HIGH     |
| 33   | What are the different phases of component lifecycle?                                               | HIGH     |
| 34   | What are the lifecycle methods of React?                                                            | HIGH     |
| 35   | What are Higher-Order components?                                                                   | HIGH     |
| 36   | How to fetch data with React Hooks?                                                                 | HIGH     |
| 37   | What is context?                                                                                    | HIGH     |
| 38   | What is children prop?                                                                              | HIGH     |
| 39   | What is prop drilling?                                                                              | MEDIUM   |
| 40   | What is the purpose of using super constructor with props argument?                                 | LOW      |
| 41   | What is reconciliation?                                                                             | HIGH     |
| 42   | How do you conditionally render components?                                                         | HIGH     |
| 43   | What are error boundaries in React v16                                                              | HIGH     |
| 44   | What are hooks?                                                                                     | HIGH     |
| 44.1 | React hooks rules                                                                                   | HIGH     |
| 45   | Why React uses className over class attribute?                                                      | LOW      |
| 46   | What are fragments?                                                                                 | HIGH     |
| 47   | Why fragments are better than container divs?                                                       | HIGH     |
| 48   | What are portals in React?                                                                          | MEDIUM   |
| 49   | What are stateless components?                                                                      | MEDIUM   |
| 50   | What are stateful components?                                                                       | MEDIUM   |
|      | **React Redux**                                                                                     | HIGH     |
| 51   | What is Flux?                                                                                       | HIGH     |
| 52   | What is Redux?                                                                                      | HIGH     |
| 52.1 | What hooks does Redux have                                                                          | HIGH     |
| 53   | What are the core principles of Redux?                                                              | HIGH     |
| 54   | What are the downsides of Redux compared to Flux?                                                   | HIGH     |
| 56   | What is the difference between mapStateToProps() and mapDispatchToProps()?                          | LOW      |
| 57   | Can I dispatch an action in reducer?                                                                | HIGH     |
| 58   | How to access Redux store outside a component?                                                      | HIGH     |
| 59   | What are the drawbacks of MVW pattern                                                               | MEDIUM   |
| 60   | Are there any similarities between Redux and RxJS?                                                  | MEDIUM   |
| 61   | How to dispatch an action on load?                                                                  | MEDIUM   |
| 62   | How to use `connect` from React Redux?                                                              | MEDIUM   |
| 63   | How to reset state in Redux?                                                                        | MEDIUM   |
| 64   | Whats the purpose of at symbol in the redux connect decorator?                                      | LOW      |
| 65   | What is the difference between React context and React Redux?                                       | HIGH     |
| 66   | Why are Redux state functions called reducers?                                                      | MEDIUM   |
| 67   | How to make AJAX request in Redux?                                                                  | MEDIUM   |
| 68   | Should I keep all component's state in Redux store?                                                 | HIGH     |
| 69   | What is the proper way to access Redux store?                                                       | HIGH     |
| 70   | What is the difference between component and container in React Redux?                              | MEDIUM   |
| 71   | What is the purpose of the constants in Redux?                                                      | HIGH     |
| 72   | What are the different ways to write mapDispatchToProps()?                                          | MEDIUM   |
| 73   | What is the use of the ownProps parameter in mapStateToProps() and mapDispatchToProps()?            | MEDIUM   |
| 74   | How to structure Redux top level directories?                                                       | MEDIUM   |
| 75   | What is redux-saga?                                                                                 | LOW      |
| 76   | What is the mental model of redux-saga?                                                             | LOW      |
| 77   | What are the differences between call and put in redux-saga                                         | LOW      |
| 78   | What is Redux Thunk?                                                                                | MEDIUM   |
| 79   | What are the differences between redux-saga and redux-thunk                                         | LOW      |
| 80   | What is Redux DevTools?                                                                             | LOW      |
| 81   | What are the features of Redux DevTools?                                                            | LOW      |
| 82   | What are Redux selectors and Why to use them?                                                       | LOW      |
| 83   | What is Redux Form?                                                                                 | LOW      |
| 84   | What are the main features of Redux Form?                                                           | LOW      |
| 85   | How to add multiple middlewares to Redux?                                                           | LOW      |
| 86   | How to set initial state in Redux?                                                                  | MEDIUM   |
| 87   | How Relay is different from Redux?                                                                  | LOW      |
| 88   | What is an action in Redux?                                                                         | HIGH     |
|      | **React Router**                                                                                    |          |
| 89   | What is React Router?                                                                               | HIGH     |
| 90   | Why do we need to React Router?                                                                     | HIGH     |
| 91   | What are the main benefits of using React Router?                                                   | HIGH     |
| 92   | How is React routing different from conventional routing?                                           | HIGH     |
| 93   | How React Router is different from history library?                                                 | MEDIUM   |
| 94   | What is the purpose of push and replace methods of history?                                         | MEDIUM   |
| 95   | How do you implement React routing?                                                                 | HIGH     |
| 96   | What is the purpose of Outlet component?                                                            | HIGH     |
| 97   | What is nested routing?                                                                             | HIGH     |
| 98   | How to do nested routing?                                                                           | HIGH     |
| 99   | How to suspense routing with route splitting?                                                       | LOW      |
| 100  | How to do redirect?                                                                                 | MEDIUM   |
| 101  | How to navigate backward and forward?                                                               | LOW      |
| 102  | How to create a protected (private) route?                                                          | HIGH     |
| 103  | What are some ways that you can share data among routes in React Router?                            | LOW      |
| 104  | What are the differences between types of routing: Hash, Browser, Memory?                           | HIGH     |
| 105  | How to get search params?                                                                           | MEDIUM   |
| 106  | How to implement default or NotFound page?                                                          | HIGH     |
| 107  | What are the differences between v5 and v6?                                                         | MEDIUM   |
| 108  | Have you ever upgraded the major version of router? If yes, what issues you faced?                  | LOW      |

# WORKING IN PROGRESS...
![img.png](img.png)
