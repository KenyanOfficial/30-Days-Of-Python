# Types of Python Frameworks

There are 3 Major categories of Python Frameworks, althought they still have other sub-categories, the 3 divisions are as follows;

**1. Full-Stack Framework**

**2. Microframework**

**3. Asynchronous Framework**

## 1. Full-Stack Framework

Such frameworks are a one-stop solution for all developer requirements. Form generators, form validation, and template layouts are usually available with a typical full-stack framework. See examples below;-

 <details><summary> <h3>A. CubicWeb</h3></summary>  
  - A. CubicWeb

Developed and curated by Logilab, CubicWeb is a free-to-use, semantic, open-source, Python-based web framework. Based on the data model, CubicWeb requires to have the same defined in order to develop a functional application. Unlike other popular Python frameworks that use separate views and models, CubicWeb makes use of cube. Multiple cubes are then joined together for creating an instance with the help of a database, a web server, and some configuration files. 

  - Key highlights:

    - OWL (Web Ontology Language) and RDF (Resource Description Framework) support
    - Reusable components
    - Security workflows
    - Simplifies data-related queries with RQL (Relational Query Language) embedding
    - Support for multiple databases.

</details>

##
## 2. Microframework

These are lightweight frameworks that don’t offer additional functionalities and features, such as database abstraction layer, form validation, and specific tools and libraries. Developers using a microframework need to add a lot of code and additional requirements manually. See examples below;-
##
## 3. Asynchronous Framework

Gaining popularity recently, any asynchronous framework is a microframework that allows for handling a large set of concurrent connections. Typically, an asynchronous framework built for Python uses the programming language’s asyncio library. See examples below;-

 <details><summary><h3>A. AIOHTTP</h3></summary>
  - A. AIOHTTP
 is a Python framework that relies heavily on Python 3.5+ features, such as async & awaits. The Python framework makes use of Python’s asyncio library, and is hence an asynchronous framework. In addition to being a server web framework, AIOHTTP can also serve as a client framework. It provides a request object and router to enable the redirection of queries to functions developed to handle the same.

  - Key highlights:

    - Allows effectively building the views
    - Middlewares support
    - Pluggable routing
    - Signals
    - Supports both Client WebSockets and Server WebSockets without the Callback Hell

</details>
