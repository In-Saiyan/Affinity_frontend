<div align="center" >
    
![img](./src/assets/readme_banner.png)

<br> 

</div>
Welcome to the Affinity Frontend repository! This project is part of the broader Affinity platform, focusing exclusively on frontend development. Affinity is a web application designed to connect individuals with similar intellectual levels. The platform utilizes an AI-powered chatbot for matchmaking and includes various interactive games, such as coding rounds, to match users based on their skillset. Once matched, users can engage in meaningful conversations with one another, fostering intellectual connections.

<br>
<br>

<div align="center">
    
 ![homepage.gif](./src/assets/homepage.gif)
</div>

<br>

If you're interested in working on the backend of our project, please head over to the following repository [Affinity Backend](https://github.com/Sidharth-Singh10/Affinity-backend).



# Navigation
<div align="center">

<br>
  <a href="#introduction"><kbd> <br> Introduction <br> </kbd></a>&ensp;&ensp;
  <a href="#features"><kbd> <br> Features <br> </kbd></a>&ensp;&ensp;
  <a href="#technologies-used"><kbd> <br> Technologies Used <br> </kbd></a>&ensp;&ensp;
  <a href="#installation"><kbd> <br> Installation <br> </kbd></a>&ensp;&ensp;
  <a href="#usage"><kbd> <br> Usage <br> </kbd></a>&ensp;&ensp;
  <a href="#routing"><kbd> <br> Routing <br> </kbd></a>&ensp;&ensp;
  <a href="#directory-tree"><kbd> <br> Directory Tree <br> </kbd></a>&ensp;&ensp;
  <a href="#contributing"><kbd> <br> Contributing <br> </kbd></a>&ensp;&ensp;
  <a href="#contact"><kbd> <br> Contact <br> </kbd></a>

<br><br> </div>


## Introduction

The Affinity Frontend is a React-based application designed to deliver a smooth and seamless user experience. This repository contains all the code related to the frontend portion of the Affinity project, and contributions should be focused solely on this area. The frontend interacts with the backend through API calls to provide matchmaking services, games, and chat functionality for users.

## Features

- User-friendly interface
- Responsive design
- Integration with backend APIs
- Routing with React Router

## Technologies Used

- React
- React Router
- Axios
- CSS Modules

## Installation

To get started with the project, follow these steps:

1. Clone the repository:

    ```bash
    git clone https://github.com/rishyym0927/Affinity_frontend.git
    cd Affinity_frontend
    ```

2. Install dependencies:

    ```bash
    npm install
    ```
3. Even after running npm install, it may give an error while running that "`dotenv is not defined`".
Simply run :

   ```bash
   npm install dotenv
   ```
   Now you can re-run the server and this time it will run without any error.

> [!Note]
> *Please note that you don’t need environment variables to run the project since no environment variables are currently being used in the codebase. The project contains only the frontend code and all the data has been hardcoaded. However, the requirement to install `dotenv` exists due to the boilerplate code present in the `vite.config.js`, which includes the `dotenv` configuration. Aside from this boilerplate setup, there is no practical need for `dotenv` in the project at the moment.*


## Usage

To run the application locally, use the following command:

```bash
npm start
```

This will start the development server and you can view the application in your browser at `http://localhost:5173`.


> [!Important]
>  Users are informed that they have the complete right to manipulate the sample data present in *sampleData.js*, as it is hardcoded. Any changes made will affect only your own codebase and will not impact others.


## Routing
> [!Warning]
> **Affinity** is still under development so it lacks connectivity between its various pages hence there is no button or something kind of that can direct you to other pages. But you can access them by using a */* followed by *page-route*.

<table align="center">
  <tr>
    <th> Page Name </th>
    <th>Route</th>
  </tr>
  <tr>
    <td>Landing</td>
    <td><a href="./src/pages/Landing.jsx">/src/pages/Landing.jsx</a></td>
  </tr>
  <tr>
    <td>Login</td>
    <td>
        <a href="./src/pages/Login.jsx">/src/pages/Login.jsx</a>
    </td>
  </tr>
  <tr>
    <td>Register</td>
    <td><a href="./src/pages/Register.jsx">/src/pages/Register.jsx</a></td>
  </tr>
  <tr>
    <td>Room Page</td>
    <td><a href="./src/pages/Room.jsx">/src/pages/Room.jsx/:roomId</a></td>
  </tr>
  <tr>
    <td>Code Run</td>
    <td><a href="./src/pages/Code Run.jsx">/src/pages/CodeRun.jsx</a></td>
  </tr>
  <tr>
    <td>Dashboard</td>
    <td><a href="./src/pages/Dashboard.jsx">/src/pages/Dashboard.jsx</a></td>
  </tr>
  <tr>
    <td>Matches</td>
    <td><a href="./src/pages/Matches.jsx">/src/pages/Matches.jsx</a></td>
  </tr>
  <tr>
    <td>Requests</td>
    <td><a href="./src/pages/Requests.jsx">/src/pages/Requests.jsx</a></td>
  </tr>
  <tr>
    <td>Queue</td>
    <td><a href="./src/pages/Queue.jsx">/src/pages/Queue.jsx</a></td>
  </tr>
  <tr>
    <td>Chatbot</td>
    <td><a href="./src/pages/Chatbot.jsx">/src/pages/Chatbot.jsx</a></td>
  </tr>
  <tr>
    <td>Denied</td>
    <td><a href="./src/pages/Denied.jsx">/src/pages/Denied.jsx</a></td>
  </tr>
</table>


## Directory tree

<div align="center>
    
  ![directory](./src/assets/directory-tree.png)
</div>

- [**public/**](./public/): Contains the static files.
- [**src/**](./src/): Contains the source code for the application.
  - [**assets/**](./src/assets/): Contains images, fonts, and other static assets.
  - [**components/**](./src/components/): Contains reusable React components.
  - [**pages/**](./src/pages/): Contains React components for different pages.
  - [**App.jsx**](./src/App.jsx): The main App component.
  - [**main.jsx**](./src/main.jsx): The entry point of the application.



## Contributing

We welcome contributions from the community! Please read our <span style="text-decoration: none;">[`CONTRIBUTING.md`](./CONTRIBUTING.md)</span> file for detailed guidelines on how to contribute to this project.

### Hacktoberfest and GSSoC 24

This repository is actively participating in Hacktoberfest and GSSoC 24. We welcome contributions, but please note that only frontend-related tasks are open for contribution. Any modifications or changes to the backend will not be considered. Feel free to raise issues and start working on assigned tasks.


## Contact

If you have any questions or need further assistance, feel free to open an issue or contact the maintainers.

Thank you for your contributions!

# Contributers



[def]: "src/assets/readme_banner.png"
