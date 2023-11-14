# front-end
front-end

## DOM

Giới thiệu về DOM [1](https://techmaster.vn/posts/34689/tim-hieu-ve-dom-document-object-model-p1-gioi-thieu), [2](https://techmaster.vn/posts/34690/tim-hieu-dom-document-object-model-p2-dom-tree-va-nodes)

## Road Map Front-End Development

http://fullbit.ca/2018-full-stack-developer-road-map-part-1-front-end-development/

## Vue.js

https://techblog.vn/tags/vuejs

# Choosing the Optimal Tech Stack
Source: Codeanywhere
https://blog.codeanywhere.com/choosing-the-optimal-tech-stack-for-your-web-application-in-2023

Developing a new web application in 2023 is both an exciting opportunity and a daunting task. The choices for languages, frameworks, databases, and infrastructure have exploded in the past decade. While abundant options provide flexibility, they also invite decision paralysis for teams starting a new project.

## 1. Aligning Your Stack with Project Goals
The first step is outlining your goals for the web app and team composition. Key elements to consider:

### 1.1. Project Scope and Timeline
Is this a simple brochure-style site or complex web application?
What is the expected traffic volume and scale?
How quickly does your app need to be developed and launched?
A smaller project may not require extensive infrastructure. But complex apps need robust and scalable foundations. Timelines influence language and framework choices to enable faster development.

### 1.2. Team Skillsets
Will you be the sole developer or are there specialized front-end/back-end roles?
Does your team have experience with certain languages or frameworks?
Playing to existing strengths will maximize productivity over learning new technologies. A single developer may prefer a full-stack framework for simplicity. Specialized roles can divide front-end and back-end technologies.

### 1.3. Maintenance Plans
Is this a short-term project or a long-term investment?
How easily can the team maintain feature development after launch?
Newer or less common languages and frameworks often have less support and higher maintenance costs long-term. Established options keep the door open for easier ongoing development.

## 2. Key Technology Choices
With project goals clarified, let's examine popular options for core components of your web app's technology stack:

### 2.1. Programming Languages
#### 2.1.1. Backend
- **JavaScript/Node.js** - Benefits from full-stack JavaScript skills. Highly scalable and productive.
- **Python** - Rapid development and vast ecosystem. Simpler for new backend developers.
- **Java/Kotlin** - Strong type safety and multithreading. Enterprise-ready performance and robustness.
- **C#/.NET** - Mature ecosystem and developer community. Cross-platform on .NET 6.
- **Go** - Excellent performance, simple deployment, and built-in concurrency. Statically typed.
- **Ruby/Rails** - Productivity oriented. Opinionated MVC structure great for standard CRUD apps.
- **PHP** - Ubiquitous language with many mature frameworks available.

#### 2.1.2. Frontend
- **JavaScript/TypeScript** - First-class front-end language with excellent ecosystem. TypeScript enhances robustness.
- **Dart** - Strongly typed language optimized for UI development. Used in Flutter apps.
For greenfield projects, using the same language on front and back ends simplifies development, sharing of code/types, and recruiting specialized developers.

But teams can mix-and-match languages to leverage existing skills. For example, combining Python and Node.js or Go and TypeScript.

### 2.2. Web Frameworks
Popular open-source web frameworks in leading languages include:

- **Node.js:** Express, Fastify, NestJS, Sails, Astro, Remix
- **Python:** Django, Flask, FastAPI
- **Java:** Spring, Micronaut, Helidon
- **C#/.NET:** ASP.NET Core, NancyFx
- **Go:** Gin, Revel, Beego
- **Ruby:** Rails, Sinatra, Padrino
- **PHP:** Laravel, Symfony, CodeIgniter
Frameworks speed development by providing routing, request handling, and boilerplate code generation. They allow focusing business logic rather than building foundations.

Full-stack frameworks like Rails and MERN provide front-end and back-end layers. Microframeworks like Express and Flask offer minimal viable features.

***Front-End Libraries/Frameworks***:

- **React** - Immensely popular for building complex UIs through composable components.
- **Angular** - Full-featured framework great for enterprise apps. Has a learning curve.
- **Vue** - Approachable and versatile. Simpler than React with great documentation.
- **Svelte** - Innovative compiler-based framework for high performance.
- **Ember** - Stable and opinionated. Excellent for CRUD apps. Lower adoption than React or Vue.
Lightweight options like Alpine.js or HTMX also exist for sprinkling interactivity into traditional server-rendered apps without a heavy framework.

### 2.3. Databases
- **PostgreSQL** - Open source SQL database with a strong reputation. Full-featured and reliable.
- **MySQL** - Popular open source SQL database. Wide support across web hosts.
- **SQLite** - Simple file-based SQL engine. Great for prototyping or simple workloads.
- **MongoDB** - Leading NoSQL document database. Flexible schemas and scaling.
- **DynamoDB** - Fully managed NoSQL database from AWS. Serverless option.
- **Redis** - In-memory data store often used for caching, queues, or sessions.
For smaller apps, SQLite or Redis may suffice initially. Larger apps typically use PostgreSQL or MySQL for relational data, and Mongo or DynamoDB for NoSQL needs.

### 2.3. Hosting and Infrastructure
- **Cloud hosts:** Heroku, AWS, GCP, Azure, DigitalOcean
- **Platforms-as-a-Service:** Netlify, Vercel, Render
- **Containers:** Docker, Kubernetes
- **Serverless:** AWS Lambda, Cloudflare Workers
Managed cloud platforms simplify deployments with auto-scaling capabilities. Containers enable predictable environments. Serverless offloads infrastructure management.

You can also host directly on virtual machines or physical servers. Consider data residency regulations when evaluating hosting providers.

## 3. Additional Considerations
Beyond core technologies, additional factors influence technology choices:

### 3.1. Learning Curve
Opt for languages and frameworks with shallower learning curves to start projects quickly. Python and Node.js are generally accessible. Frameworks like Express, Django, and Ruby on Rails rapid prototypes.

### 3.2. Community and Ecosystem
Languages and frameworks with larger communities provide more support resources, tutorials, Stack Overflow answers, and available libraries and integrations.

### 3.3. Maturity and Stability
Proven technologies have passed the test of time. Bleeding edge options often lack robust tooling and risk being passing fads.

### 3.4. Performance
Traffic demands and complexity dictate technology choices. C++/Rust offer native speed. Java and Go provide excellent throughput. Some frameworks carry more overhead.

### 3.5. Type Safety
Languages like Java, C#, and TypeScript enable declaring data types for reliability. Others like Python and Ruby are dynamically typed.

There are always tradeoffs balancing these considerations for your app's specific needs. Don't prematurely optimize based on assumptions - you can evolve the stack as requirements become clearer post-launch.

## 4. Template Tech Stacks to Guide Your Decisions
With an overview of critical choices across languages, frameworks, databases and infrastructure, let's examine some proven template stacks that serve as starting points for many web applications:

### 4.1. JavaScript/Node/React
- Backend: Node.js, Express
- Frontend: React, Next.js
- Database: PostgreSQL, MongoDB
- Infrastructure: AWS, Vercel, Docker
Node.js provides high productivity and scalability. React's component model enables complex UIs. MongoDB supplements PostgreSQL's relational data store. Deployment options span traditional cloud hosts to modern platforms.

This stack enables full-stack JavaScript development and shares knowledge across the team. React's popularity makes hiring simpler. The extensive ecosystem provides myriad libraries for app needs.

Potential drawbacks are JavaScript fatigue - the endless influx of new frameworks and paradigms to keep pace with. There is also risk of over-engineering or over-architecting apps.

### 4.2. Python/Django/React
- Backend: Django (Python)
- Frontend: React, Next.js
- Database: PostgreSQL
- Infrastructure: Heroku, AWS, GCP
This combination leverages Python's fast development cycle and Django's batteries-included web framework together with React's advanced UI capabilities.

Django simplifies back-end REST APIs and sites. React adds front-end flexibility without giving up back-end simplicity. The end result is reliable and scalable.

Downsides are context switching between languages and splitting skills rather than full-stack JS. Asynchronous Django support also lags behind Node.

### 4.3. Ruby on Rails
- Backend: Ruby on Rails
- Frontend: Rails, ERB, or Vue
- Database: PostgreSQL
- Infrastructure: Heroku, AWS
Rails pioneered conventions over configuration with a prescriptive MVC structure. This enables rapid modeling of data and routes into working features with little code.

Adding a modern front-end framework like Vue combines productivity with front-end flexibility. The community is smaller than JavaScript or Python.

Rails remains excellent for standard CRUD business apps. But it has scaling limitations relative to Go or Elixir/Phoenix for high-traffic apps.

### 4.4. Java/Spring Boot/React
- Backend: Spring Boot (Java)
- Frontend: React
- Database: PostgreSQL, MongoDB
- Infrastructure: AWS, Pivotal, Azure, On-prem
For enterprise apps, Java brings static typing, excellent performance, and robust tooling. Spring Boot simplifies configuration bringing Rails-like convention over configuration.

React or Angular handle complex UIs with TypeScript for additional type safety. Broad infrastructure deployment options support hybrid cloud needs.

The benefits come at the cost of verbosity compared to languages like Go or Python. But Spring Boot with Lombok helps reduce boilerplate code.

### 4.5. Go / Vue
- Backend: Go
- Frontend: Vue, Nuxt.js
- Database: PostgreSQL, Redis, MongoDB
- Infrastructure: AWS, GCP, DigitalOcean
Go's performance and simplicity pairs well with Vue's approachability on the front end.

Go removes overhead enabling fast boot times and efficient scaling. Vue has gentle learning curve and is lighter than React.

Downsides are smaller communities vs languages like JavaScript. And more limited framework choices compared to Java or C#.

### 4.6. Sumary:
To help guide your decisions, I've included some template tech stacks that serve as starting points for many web applications:
- **JavaScript/Node/React:** Backend - Node.js/Express, Frontend - React/Next.js, Database - PostgreSQL/MongoDB, Infrastructure - AWS/Vercel/Docker
- **Python/Django/React:** Backend - Django (Python), Frontend - React/Next.js, Database - PostgreSQL, Infrastructure - Heroku/AWS/GCP
- **Ruby on Rails:** Backend - Ruby on Rails, Frontend - Rails/ERB or Vue, Database - PostgreSQL, Infrastructure - Heroku/AWS
- **Java/Spring Boot/React:** Backend - Spring Boot (Java), Frontend - React, Database - PostgreSQL/MongoDB, Infrastructure - AWS/Pivotal/Azure
- **Go/Vue:** Backend - Go, Frontend - Vue/Nuxt.js, Database - PostgreSQL/Redis/MongoDB, Infrastructure - AWS/GCP/DigitalOcean

## 5. Build, Measure, Learn: Optimize Your Stack Iteratively
There is no one-size-fits all technology stack. The needs of an e-commerce site differ greatly from those of a real-time chat application. Languages and frameworks carry trade-offs around productivity, performance, and ecosystem.

The best approach is to make initial practical choices geared for speed, then evolve the stack as bottlenecks or limitations emerge. Resist over-engineering based on fragile predictions.

The multitude of choices available today empowers you to assemble a custom technology stack catered to your app's specific needs and team composition. Doing so requires balancing factors like performance, scalability, productivity, and ecosystem support against project timelines and complexity.

In conclusion, effective development environment is crucial for successful web application development. 

## Referral

- Phan Hữu Hào, *Tìm hiểu về DOM - Document Object Model* [1](https://techmaster.vn/posts/34689/tim-hieu-ve-dom-document-object-model-p1-gioi-thieu), [2](https://techmaster.vn/posts/34690/tim-hieu-dom-document-object-model-p2-dom-tree-va-nodes)
- Colin, [2018 Full Stack Developer Road Map: Part 1 – Front End Development](http://fullbit.ca/2018-full-stack-developer-road-map-part-1-front-end-development/)
