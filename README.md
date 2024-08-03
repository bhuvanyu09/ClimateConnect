<div align="center">

# Weather Sense

</div>

This repository contains a full-stack project developed using the MERN stack (MongoDB, Express.js, React, and Node.js) that fetches local weather data from weather API and displays it on the dashboard.

https://github.com/kunaal-gupta/WeatherSense/assets/87749508/48ce969f-074f-4bd9-8096-5e184201b8a0

## Frontend

The frontend of this 


project is meticulously crafted using React, a powerful JavaScript library. It serves as the backbone of the application, handling routing and rendering of multiple sub-components, including the visually appealing dashboard page, welcoming page, and the intuitive login/register pages. These pages are thoughtfully designed utilizing a blend of HTML, CSS, and JavaScript, ensuring an engaging and seamless user experience.

To fetch data from the Weather API and interact with the MongoDB database, the project leverages the Axios library. Axios provides a convenient and efficient way to make GET/POST requests, facilitating the retrieval and manipulation of data in a secure manner. By integrating Axios, the frontend seamlessly communicates with the backend, enabling smooth data exchange between the application and external APIs.

## Backend

The backend of this project is built using Express.js and Node.js, serving as a robust bridge between the React frontend and the database. It enables seamless communication and facilitates the retrieval of weather data by leveraging Express's powerful GET/POST functionality.

For efficient data storage and management, the project utilizes a MongoDB database hosted on MongoDB Atlas. The database consists of two collections: "Active Users" for currently logged-in users and "Registered Users" for storing details of registered users like name, email, password, and city.

![WelcomePage](https://github.com/kunaal-gupta/WeatherSense-Project/assets/87749508/4e071391-8239-437c-9075-4d04ae09cf3c)
![LoginPage](https://github.com/kunaal-gupta/WeatherSense-Project/assets/87749508/256fc740-3efd-40df-8e74-a05b2a316b9f)
![RegisterPage](https://github.com/kunaal-gupta/WeatherSense-Project/assets/87749508/24076d4c-5528-47ad-8d03-4e3e345bf65b)
![Dashboard](https://github.com/kunaal-gupta/WeatherSense-Project/assets/87749508/1f6d85ea-d3fd-44e1-afbf-e3fdeb53bae5)



## Authors

- [@Kunaal Gupta](https://github.com/kunaal-gupta)

[![portfolio](https://img.shields.io/badge/my_portfolio-000?style=for-the-badge&logo=ko-fi&logoColor=white)](https://kunaal-gupta.github.io/)
[![linkedin](https://img.shields.io/badge/linkedin-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/iamkunaalgupta/)



## Installation and Setup

```bash
git clone https://github.com/kunaal-gupta/WeatherSense.git
```
```bash
npm install
```

# Running App

**Server-side Application**

```bash
  cd server
```

```bash
  npm install
```

```bash
  npm run dev
```

**Client-side Application**

```bash
  cd server
```

```bash
  npm install
```

```bash
  npm start
```

## Dependencies
- <a href = 'https://fontawesome.com/start'> Font Awesome Icons <a/>: Library for Font Awesome solid style icons.
    ```bash
    npm i --save @fortawesome/fontawesome-svg-core
    ```
- <a href = 'https://www.npmjs.com/package/react-router-dom'> React Router Dom:</a> Package which enables client side routing in React applications.
    ```bash
    npm i react-router-dom
    ```
- <a href ='https://react-icons.github.io/react-icons/icons?name=wi'>React Icons:</a> Library for popular icons in your React projects
   ```bash
  npm install react-icons --save
  ```

- <a href ='https://apexcharts.com/docs/react-charts/'>Apexcharts.JS:</a> Library for interactive charts in React using ApexCharts
  ```bash
  npm install apexcharts --save
  ```



## Tech Stack

**Frontend:** React

**Backend:** Node, Express 

**Database:** MongoDB
    


## Features

- Fetches weather data from an API every minute and displays it in the frontend
- Allows users to register and login to access personalized weather information
- Stores user data, including name, email, password, and city, in a MongoDB database
- Provides a responsive user interface with routing and sub-component rendering using React


## Contributing

Contributions are always welcome!

If you encounter any bugs or would like to suggest improvements, please open an issue or submit a pull request.



