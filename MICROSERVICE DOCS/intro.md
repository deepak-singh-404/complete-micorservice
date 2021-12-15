Software Architecture pattern

Microservices:
--Robust Architecture
--Independent of runtime and database
--Companies using microservices [netflix, facebook, uber, ebay etc.]

History
-Monolith 
 CONS:
    All Software components are executed in Single Process, Sharing Same Memory,
    Strong coupling between classes
    single codebase (cant use multiple run time, multiple db support)
    Cumbersome
  PROS:
    Easier to Design
-SOA
    Service oriented Architecure
    Talks with the help of API

PROBLEM WITH MONOLITH AND SOA PARADIGMS
--Single technology platform 
--Inflexible Deployment [Force to deploy whole app, if we change small changes too, that tends to regres testing]
--Inefficient compute resources [horizontol scaling]
--Large and complex
--Enterprise Service Bus (Expensive ESB)
--Lack of Tooling
--No time of saving


MICROSERVICE
--Modular
--2011 came into world.
--in 2014 become popular.

Charatersitic of Microservices
--Componentization via services
--Organized Around Business Capabilities
--Products not projects
--Smart Endpoints and Dumb pipes
--Decentralized govenrnance
--Decentalized Data management
--Infrasturcture Data management
--Infrastructire Automation
--Design for failure
--Evolutionary Design




COMPONENTIZATION OF MICROSERVICES
--Modular design is always a good idea.
--Run on single process.
--Independent Deployment
--Horizontol Scaling

ORGANIZED AROUND BUSINESS CAPABILITIES


PRODUCTS NOT PROJECTS


DECENTRALIZED GOVENRNANCE
With microservices each team make its own decision
--Which dev platform to use
--Which database to use
--How logs are created
loosely coupled nature


DECENTRALIZED DATABASE
With microservice each service has it own database.
Not always possible
Raise problem such as distributed transactions, data duplication and many more





