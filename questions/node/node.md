# Node Interview Questions

Number of questions: Total = 79; High = 24; Medium = 27; Low = 28.

### Table of Contents

#### Week 1 (Questions with High priority)
Number of questions: High = 24. 
Estimate: ~30m*24 = 12h / 5d = 2h 24m per day.

| Index | No.      | Questions                                                                                      | Priority |
|-------|----------|------------------------------------------------------------------------------------------------|----------|
|       | **1**    | **Node.js**                                                                                    |          |
|   1   | 1.1      | What is Node.js?                                                                               | High     |
|   3   | 1.3      | What is package.json?                                                                          | High     |
|   7   | 1.7      | How Event Loop works?                                                                          | High     |
|   8   | 1.8      | Is Node.js entirely based on a single-thread?                                                  | High     |
|  10   | 1.10     | What kinds of streams does Node.js have?                                                       | High     |
|       | **2**    | **Dealing with async code**                                                                    |          |
|  16   | 2.1      | How do you understand the Callback Pattern? What is a callback hell?                           | High     |
|  17   | 2.2      | What is a Promise?                                                                             | High     |
|  18   | 2.3      | What states does the Promise have? Can the state be changed once it was fulfilled or rejected? | High     |
|       | **3**    | **Express.js**                                                                                 |          |
|  23   | 3.3      | What are the purposes for middlewares in Express.js?                                           | High     |
|       | **6**    | **Testing**                                                                                    |          |
|  32   | 6.1      | What is a test pyramid? How can you implement it regarding HTTP APIs?                          | High     |
|  36   | 6.5      | What is Unit-testing? What are the FIRST principles?                                           | High     |
|       | **7**    | **Software design**                                                                            |          |
|  37   | 7.1      | REST API: What is it?                                                                          | High     |
|  40   | 7.1.3    | REST API: Name the main Http methods. What is the difference between Put and Patch?            | High     |
|  42   | 7.2      | explain the MVC model.                                                                         | High     |
|  44   | 7.4      | Name the key principles of OOP?                                                                | High     |
|       | **8**    | **Databases**                                                                                  |          |
|       | 8.1      | **_RDBMS_ (Postgres or MySQL)**                                                                |          |
|  47   | 8.1.0    | RDBMS: What is it?                                                                             | High     |
|  48   | 8.1.1    | How data is stored in RDBMS?                                                                   | High     |
|  53   | 8.1.6    | How tables can be joined?                                                                      | High     |
|  55   | 8.1.8    | Explain Transactions and ACID.                                                                 | High     |
|  57   | 8.1.10   | What type of indexes do you know? When to use them?                                            | High     |
|       | 8.1.12   | **TypeORM**                                                                                    |          |
|  63   | 8.1.12.5 | - How to change an already defined table structure with typeorm?                               | High     |
|       | 8.2      | **_NoSQL DB_**                                                                                 |          |
|  64   | 8.2.1    | What is MongoDB?                                                                               | High     |
|  68   | 8.2.5    | How scaling of NoSQL and SQL databases differs?                                                | High     |
|       | **9**    | **Security**                                                                                   |          |
|  75   | 9.7      | What is JWT? Is it safe to store sensitive information inside JWT?                             | High     |

#### Week 2 (Questions with Medium priprity)
Number of questions: Medium = 27.
Estimate: ~30m*27 = 13h 30m / 5d = 2h 42m per day.

| Index | No.      | Questions                                                                                      | Priority |
|-------|----------|------------------------------------------------------------------------------------------------|----------|
|       | **1**    | **Node.js**                                                                                    |          |
|   2   | 1.2      | When to use Node.js and when not to use it?                                                    | Medium   |
|   5   | 1.5      | What is npm?                                                                                   | Medium   |
|   6   | 1.6      | What is the difference between Sync vs Async operations?                                       | Medium   |
|  11   | 1.11     | When Streams can be used in Node.js?                                                           | Medium   |
|  15   | 1.15     | What is a Memory Leak? How to prevent it?                                                      | Medium   |
|       | **2**    | **Dealing with async code**                                                                    |          |
|  19   | 2.4      | What are the advantages of the async/await over Promises?                                      | Medium   |
|       | **3**    | **Express.js**                                                                                 |          |
|  21   | 3.1      | What is Express.js and what is its use?                                                        | Medium   |
|  22   | 3.2      | What are the main building blocks of Express.js?                                               | Medium   |
|  24   | 3.4      | What is the use of **next** in Express.js?                                                     | Medium   |
|       | **4**    | **NestJS**                                                                                     |          |
|       | **6**    | **Testing**                                                                                    |          |
|  33   | 6.2      | What is a Given-When-Then pattern?                                                             | Medium   |
|  34   | 6.3      | What mocks and stubs are? How are they used in integration testing?                            | Medium   |
|       | **7**    | **Software design**                                                                            |          |
|  39   | 7.1.2    | REST API: What constraints does the REST have?                                                 | Medium   |
|  41   | 7.1.4    | REST API: What status should be sent in a response to a create object request?                 | Medium   |
|  45   | 7.5      | What is a dependency injection?                                                                | Medium   |
|  46   | 7.6      | What is a Layered Architecture? Give a few examples                                            | Medium   |
|       | **8**    | **Databases**                                                                                  |          |
|       | 8.1      | **_RDBMS_ (Postgres or MySQL)**                                                                |          |
|  49   | 8.1.2    | What is a normalization concept?                                                               | Medium   |
|  50   | 8.1.3    | What table relationships do you know? How to create them?                                      | Medium   |
|  51   | 8.1.4    | What is the difference between DDL and DML?                                                    | Medium   |
|       | 8.1.12   | **TypeORM**                                                                                    |          |
|       | 8.2      | **_NoSQL DB_**                                                                                 |          |
|  65   | 8.2.2    | How data is orginized in MongoDB?                                                              | Medium   |
|  66   | 8.2.3    | What does the BASE stand for?                                                                  | Medium   |
|  67   | 8.2.4    | How to make a relationship between Documents in MongoDB?                                       | Medium   |
|       | **9**    | **Security**                                                                                   |          |
|  69   | 9.1      | What is the difference among Encoding, Encryption and Hashing?                                 | Medium   |
|  70   | 9.2      | What are the use cases for Encoding, Encryption and Hashing?                                   | Medium   |
|  73   | 9.5      | What is HTTPS? How it works?                                                                   | Medium   |
|  74   | 9.6      | What is Authentication and Authorization?                                                      | Medium   |
|       | **10**   | **General questions**                                                                          |          |
|  77   | 13.1     | Name the main advantages of Microservice architecture over Monolith                            | Medium   |
|  78   | 13.2     | How do you understand an event-driven architectures? What is a pub-sub pattern?                | Medium   |

#### Week 3 (Questions with Low priority)
Number of questions: Medium = 28.
Estimate: ~30m*28 = 14h / 5d = ~2h 48m per day.

| Index | No.      | Questions                                                                                      | Priority |
|-------|----------|------------------------------------------------------------------------------------------------|----------|
|       | **1**    | **Node.js**                                                                                    |          |
|   4   | 1.4      | What is the difference between dependencies and devDependencies in package.json?               | Low      |
|   9   | 1.9      | What is the Event Emitter class? How it is related to other classes?                           | Low      |
|  12   | 1.12     | What are the differences between worker thread and child_process?                              | Low      |
|  13   | 1.13     | What is the difference between commonJS and ES modules?                                        | Low      |
|  14   | 1.14     | How to force node.js to treat your  .js files as ES modules?                                   | Low      |
|       | **2**    | **Dealing with async code**                                                                    |          |
|  20   | 2.5      | What is Promisification and when it is used?                                                   | Low      |
|       | **3**    | **Express.js**                                                                                 |          |
|  25   | 3.5      | How can you differ an error handling function from a request handler function?                 | Low      | 
|       | **4**    | **NestJS**                                                                                     |          |
|  26   | 4.1      | What can be a Provider in NestJS?                                                              | Low      |
|  27   | 4.2      | What are the use cases for Pipes in NestJS?                                                    | Low      |
|  28   | 4.3      | Is there a possibility to bind extra logic before/after method execution in NestJS?            | Low      |
|  29   | 4.4      | How all unhandled exceptions are processed in NestJS?                                          | Low      |
|       | **5**    | **Monitoring and Logging**                                                                     | Low      |
|  30   | 5.1      | What is a Health check? Why do we need it?                                                     | Low      |
|  31   | 5.2      | What is a correlation ID? How it helps to debug your application?                              | Low      |
|       | **6**    | **Testing**                                                                                    |          |
|  35   | 6.4      | What test runner libraries do you know?                                                        | Low      |
|       | **7**    | **Software design**                                                                            |          |
|  38   | 7.1.1    | REST API: What are the Levels of REST API?                                                     | Low      |
|  43   | 7.3      | What is GraphQL? What are its advantages over REST API?                                        | Low      |
|       | **8**    | **Databases**                                                                                  |          |
|       | 8.1      | **_RDBMS_ (Postgres or MySQL)**                                                                |          |
|  52   | 8.1.5    | What data types are presented in PostgreSQL?                                                   | Low      |
|  54   | 8.1.7    | What is a sub query?                                                                           | Low      |
|  56   | 8.1.9    | What are Lock Levels in Postgres?                                                              | Low      |
|  58   | 8.1.11   | What is ORM? What problems does it solve?                                                      | Low      |
|       | 8.1.12   | **TypeORM**                                                                                    |          |
|  59   | 8.1.12.1 | - What is the Query Builder?                                                                   | Low      |
|  60   | 8.1.12.2 | - What are Active Record and Data Mapper patterns?                                             | Low      |
|  61   | 8.1.12.3 | - What is the difference between Raw Entities and Entities?                                    | Low      |
|  62   | 8.1.12.4 | - How to process tables with a lot of data inside with typeorm?                                | Low      |
|       | **9**    | **Security**                                                                                   |          |
|  71   | 9.3      | How do you understand symmetric and asymmetric encryption?                                     | Low      |
|  72   | 9.4      | What is the difference between private and public key?                                         | Low      |
|  76   | 9.8      | What types of Authentication do you know? When to use them?                                    | Low      |
|       | **10**   | **General questions**                                                                          |          |
|  79   | 13.3     | What is a 3-tier WEB Application? Are the tiers logical or physical?                           | Low      |

### Table of Contents by topics

| Index | No.      | Questions                                                                                      | Priority |
|-------|----------|------------------------------------------------------------------------------------------------|----------|
|       | **1**    | **Node.js**                                                                                    |          |
|   1   | 1.1      | What is Node.js?                                                                               | High     |
|   2   | 1.2      | When to use Node.js and when not to use it?                                                    | Medium   |
|   3   | 1.3      | What is package.json?                                                                          | High     |
|   4   | 1.4      | What is the difference between dependencies and devDependencies in package.json?               | Low      |
|   5   | 1.5      | What is npm?                                                                                   | Medium   |
|   6   | 1.6      | What is the difference between Sync vs Async operations?                                       | Medium   |
|   7   | 1.7      | How Event Loop works?                                                                          | High     |
|   8   | 1.8      | Is Node.js entirely based on a single-thread?                                                  | High     |
|   9   | 1.9      | What is the Event Emitter class? How it is related to other classes?                           | Low      |
|  10   | 1.10     | What kinds of streams does Node.js have?                                                       | High     |
|  11   | 1.11     | When Streams can be used in Node.js?                                                           | Medium   |
|  12   | 1.12     | What are the differences between worker thread and child_process?                              | Low      |
|  13   | 1.13     | What is the difference between commonJS and ES modules?                                        | Low      |
|  14   | 1.14     | How to force node.js to treat your  .js files as ES modules?                                   | Low      |
|  15   | 1.15     | What is a Memory Leak? How to prevent it?                                                      | Medium   |
|       | **2**    | **Dealing with async code**                                                                    |          |
|  16   | 2.1      | How do you understand the Callback Pattern? What is a callback hell?                           | High     |
|  17   | 2.2      | What is a Promise?                                                                             | High     |
|  18   | 2.3      | What states does the Promise have? Can the state be changed once it was fulfilled or rejected? | High     |
|  19   | 2.4      | What are the advantages of the async/await over Promises?                                      | Medium   |
|  20   | 2.5      | What is Promisification and when it is used?                                                   | Low      |
|       | **3**    | **Express.js**                                                                                 |          |
|  21   | 3.1      | What is Express.js and what is its use?                                                        | Medium   |
|  22   | 3.2      | What are the main building blocks of Express.js?                                               | Medium   |
|  23   | 3.3      | What are the purposes for middlewares in Express.js?                                           | High     |
|  24   | 3.4      | What is the use of **next** in Express.js?                                                     | Medium   |
|  25   | 3.5      | How can you differ an error handling function from a request handler function?                 | Low      | 
|       | **4**    | **NestJS**                                                                                     |          |
|  26   | 4.1      | What can be a Provider in NestJS?                                                              | Low      |
|  27   | 4.2      | What are the use cases for Pipes in NestJS?                                                    | Low      |
|  28   | 4.3      | Is there a possibility to bind extra logic before/after method execution in NestJS?            | Low      |
|  29   | 4.4      | How all unhandled exceptions are processed in NestJS?                                          | Low      |
|       | **5**    | **Monitoring and Logging**                                                                     | Low      |
|  30   | 5.1      | What is a Health check? Why do we need it?                                                     | Low      |
|  31   | 5.2      | What is a correlation ID? How it helps to debug your application?                              | Low      |
|       | **6**    | **Testing**                                                                                    |          |
|  32   | 6.1      | What is a test pyramid? How can you implement it regarding HTTP APIs?                          | High     |
|  33   | 6.2      | What is a Given-When-Then pattern?                                                             | Medium   |
|  34   | 6.3      | What mocks and stubs are? How are they used in integration testing?                            | Medium   |
|  35   | 6.4      | What test runner libraries do you know?                                                        | Low      |
|  36   | 6.5      | What is Unit-testing? What are the FIRST principles?                                           | High     |
|       | **7**    | **Software design**                                                                            |          |
|  37   | 7.1      | REST API: What is it?                                                                          | High     |
|  38   | 7.1.1    | REST API: What are the Levels of REST API?                                                     | Low      |
|  39   | 7.1.2    | REST API: What constraints does the REST have?                                                 | Medium   |
|  40   | 7.1.3    | REST API: Name the main Http methods. What is the difference between Put and Patch?            | High     |
|  41   | 7.1.4    | REST API: What status should be sent in a response to a create object request?                 | Medium   |
|  42   | 7.2      | explain the MVC model.                                                                         | High     |
|  43   | 7.3      | What is GraphQL? What are its advantages over REST API?                                        | Low      |
|  44   | 7.4      | Name the key principles of OOP?                                                                | High     |
|  45   | 7.5      | What is a dependency injection?                                                                | Medium   |
|  46   | 7.6      | What is a Layered Architecture? Give a few examples                                            | Medium   |
|       | **8**    | **Databases**                                                                                  |          |
|       | 8.1      | **_RDBMS_ (Postgres or MySQL)**                                                                |          |
|  47   | 8.1.0    | RDBMS: What is it?                                                                             | High     |
|  48   | 8.1.1    | How data is stored in RDBMS?                                                                   | High     |
|  49   | 8.1.2    | What is a normalization concept?                                                               | Medium   |
|  50   | 8.1.3    | What table relationships do you know? How to create them?                                      | Medium   |
|  51   | 8.1.4    | What is the difference between DDL and DML?                                                    | Medium   |
|  52   | 8.1.5    | What data types are presented in PostgreSQL?                                                   | Low      |
|  53   | 8.1.6    | How tables can be joined?                                                                      | High     |
|  54   | 8.1.7    | What is a sub query?                                                                           | Low      |
|  55   | 8.1.8    | Explain Transactions and ACID.                                                                 | High     |
|  56   | 8.1.9    | What are Lock Levels in Postgres?                                                              | Low      |
|  57   | 8.1.10   | What type of indexes do you know? When to use them?                                            | High     |
|  58   | 8.1.11   | What is ORM? What problems does it solve?                                                      | Low      |
|       | 8.1.12   | **TypeORM**                                                                                    |          |
|  59   | 8.1.12.1 | - What is the Query Builder?                                                                   | Low      |
|  60   | 8.1.12.2 | - What are Active Record and Data Mapper patterns?                                             | Low      |
|  61   | 8.1.12.3 | - What is the difference between Raw Entities and Entities?                                    | Low      |
|  62   | 8.1.12.4 | - How to process tables with a lot of data inside with typeorm?                                | Low      |
|  63   | 8.1.12.5 | - How to change an already defined table structure with typeorm?                               | High     |
|       | 8.2      | **_NoSQL DB_**                                                                                 |          |
|  64   | 8.2.1    | What is MongoDB?                                                                               | High     |
|  65   | 8.2.2    | How data is orginized in MongoDB?                                                              | Medium   |
|  66   | 8.2.3    | What does the BASE stand for?                                                                  | Medium   |
|  67   | 8.2.4    | How to make a relationship between Documents in MongoDB?                                       | Medium   |
|  68   | 8.2.5    | How scaling of NoSQL and SQL databases differs?                                                | High     |
|       | **9**    | **Security**                                                                                   |          |
|  69   | 9.1      | What is the difference among Encoding, Encryption and Hashing?                                 | Medium   |
|  70   | 9.2      | What are the use cases for Encoding, Encryption and Hashing?                                   | Medium   |
|  71   | 9.3      | How do you understand symmetric and asymmetric encryption?                                     | Low      |
|  72   | 9.4      | What is the difference between private and public key?                                         | Low      |
|  73   | 9.5      | What is HTTPS? How it works?                                                                   | Medium   |
|  74   | 9.6      | What is Authentication and Authorization?                                                      | Medium   |
|  75   | 9.7      | What is JWT? Is it safe to store sensitive information inside JWT?                             | High     |
|  76   | 9.8      | What types of Authentication do you know? When to use them?                                    | Low      |
|       | **10**   | **General questions**                                                                          |          |
|  77   | 13.1     | Name the main advantages of Microservice architecture over Monolith                            | Medium   |
|  78   | 13.2     | How do you understand an event-driven architectures? What is a pub-sub pattern?                | Medium   |
|  79   | 13.3     | What is a 3-tier WEB Application? Are the tiers logical or physical?                           | Low      |

Code snippets to debug:
```
1.
    const one = () => Promise.resolve("One!");

    async function myFunc() {
        console.log("In Function!");
        const res = await one();
        console.log(res);
    }

    console.log("Before Function!");
    myFunc();
    console.log("After Function!");
    
2.
    (async()=>{
    const one = () => Promise.resolve("One!");
    
    async function myFunc() {
        console.log("In Function!");
        const res = await one();
        console.log(res);
    }
    
    console.log("Before Function!");
    await myFunc();
    console.log("After Function!");
    })();

3.
    let a = { b:1 };
    
    function changer(a) {
        a = { b: 2 };
    }
    
    changer(a);
    console.log(a.b);

4.
    const a = {
        b:1
    };
    
    function changer(a) {
        a.b = 2;
    }
    changer(a);
    
    console.log(a.b)
 ```