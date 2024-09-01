# Node.js Learners Package

## Description

This package offers a concise introduction to Node.js (using JupyterLab), focusing only on the essential concepts and skills. It covers the fundamental topics necessary for understanding and practicing (or reviewing) Node.js, including:

- [Introduction](01-intro.ipynb) 
- [JSON Handling](02-objects.ipynb) 
- [Working with Arrays](03-objects.ipynb) 
- [Working with Maps](04-maps.ipynb)
- [Working with Sets](05-sets.ipynb)
- [Functions](06-functions.ipynb)
- [Files Operations](07-files.ipynb)
- [Async-await, Promise and Events](08-asyncs.ipynb)
- [Simple HTTP server](09-http-server.ipynb) + [helper client](09-http-client.ipynb)
- [MongoDB](10-mongodb.ipynb) 
- [Mongoose](11-mongoose.ipynb)
- [RESTful API using Express](12-express-server.ipynb) + [helper client](12-express-client.ipynb)


## Who should use this?

This project is designed for **intermediate-level** developers who are looking to deepen their understanding of *core concepts* in [Node.js](https://nodejs.org/) and [JS](https://javascript.com/). It is particularly beneficial for those who want to expand their knowledge, **review general principles**, or gain a broader perspective on [Node.js](https://nodejs.org/) and [JS](https://javascript.com/). If you are an **expert** in this field, you might find the material **NOT** directly applicable to advanced scenarios. However, if you are eager to refresh your foundational skills or explore different approaches, this resource may still offer valuable insights

## Active Development

Please note that this package is *actively being modified and updated*. We are continuously working to improve and expand the content based on feedback and new developments in [Node.js](https://nodejs.org/). New features, topics, and enhancements will be added over time. To ensure you have the *latest dependencies and updates*, you might need to run `npm install` periodically.

## Features

- **Variables and Functions**: Learn how to create and use *variables*, *functions* and *lambdas*.
- **Loops and Branching**: Understand different looping constructs and conditional statements.
- **JSON**: Work with *JSON* data, including parsing and stringifying *JSON*.
- **Collections**: Explore *arrays*, *maps*, and *sets*, and how to manipulate them.
- **File Handling**: Read from and write to files.
- **Async-await, Promise and Events**: Learn how to do *asynchronous* operations with *async-await*, *promise* and *events*.
- **Fetch and Axios**: Learn how to use *fetch* and *axios* to send request.
- **HTTP Connections**: Create basic HTTP servers and handle requests and responses.
- **MongoDB and Mongoose**: Connect to a [MongoDB](https://www.mongodb.com) database and perform CRUD operations using [Mongoose](https://www.mongoosejs.com).
- **Express**: Build simple with *RESTfull* api *authentioncation-authorization* using the [Express framework](https://www.expressjs.com).
- **And More...**

## Installation

To get started with this package, follow these steps:

1. **Install Node.js**:
   - Ensure you have [Node.js](https://nodejs.org/) installed. This is required for running Node.js apps in this package.

2. **Install the Node.js Jupyter Kernel**:
   - You need the [IJavascript kernel](https://github.com/n-riesco/ijavascript) for Jupyter to run JavaScript code. You can install it using the following commands:
     ```bash
     npm install -g ijavascript
     ijsinstall
     ```

3. **Clone the Repository**:
    ```bash
    git clone https://github.com/me-moghadasian/nodejs-learners-package.git
    ```

4. **Navigate into the Project Directory**:
    ```bash
    cd nodejs-learners-package
    ```

5. **Install Project Dependencies**:
    - Install MongoDB too when you want to try MongoDB related sections.
    ```bash
    npm install
    ```

7. **Install JupyterLab** (if not already installed):
   - If you don't have JupyterLab installed, you'll need Python and JupyterLab. You can install JupyterLab using:
    ```bash
    pip install jupyterlab
    ```

8. **Start JupyterLab**:
    ```bash
    jupyter lab
    ```

9. **Open and Explore the Notebooks and Scripts**:
   - Use JupyterLab to open and explore the notebooks and scripts provided in the package.

## Note

This package is still under development. New features and improvements will be added over time. you might need to run `npm install` periodically.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Author

Mehdi Moghadasian
