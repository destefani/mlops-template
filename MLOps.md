# MLOps
Notes on MLOps from the book [*Practial MLOps*](https://www.oreilly.com/library/view/practical-mlops/9781098103002/) by Noah Gift and Alfredo Daeza

## What is MLops?
MLOps is the process of automating machine learning using [DevOps](https://en.wikipedia.org/wiki/DevOps) methodologies.

## DevOps and MLOps

DevOps is a set of technical and management practices that aim to increase n organization's velocity in realising high quality software. The main practices in the DevOps process are:
- [**Continuous integration**](https://en.wikipedia.org/wiki/Continuous_integration) (CI): Is the process of continuosly testing a software project and improving the quality based on these tests' results.

- [**Continuous delivery**](https://en.wikipedia.org/wiki/Continuous_delivery) (CD): This method delivers code to a new enviromentwithout human intervention. This is the process of deploying code automatically, often through the use of IaC.

- [**Microservices**](https://en.wikipedia.org/wiki/Microservices): A microservice is a software service with a distinct function that had little to no dependencies.

- [**Infrastructure as Code**](https://en.wikipedia.org/wiki/Infrastructure_as_code): Is the process of checking the infrastructure into a source repository and "deploying" it to push changes to that repository. It ensures that infrastructure doesn'y require humans to build out.
- **Monitoring and instrumentation**:This are the processes and techniques used that allow an organization to make decisions about software system's performance and reliability. Monitoring and instrumentation is essentially collecting data about the behaviour of an application in production or data science for deployed software systems.

- **Effective technical communication**: This skill involves the avility to create effective, repeatable, and efficient communication methods.

- **Effective technical project management**: This process cam efficiently use human and technology solutions, like ticket system and spreadsheets, to manage projects. Also, appropiate technical project management requires breaking down problems into small, discrete chunks of work, so incremental progress occurs.