<br />
<div align="center">
  <a href="https://github.com/DaniilZotin/Spring-users-system">
    <img src="Images/logo.png" alt="Logo" width="300" height="150">
  </a>

<h3 align="center" >Full stack analytics system</h3>

</div>

## Introduction
Hi, this repo has full stack project to show and analyze data from advertisements.


## About the project
A system for working with analytics that has endpoints, they have two types:

1. Endpoints that implemeted for main purpose of program<br/>
$\color{#55AE5B}{{GET}}$ /api/analytics/getDataAnalytics - Show all analytics data in the system<br/>

2. Endpoints that implemeted for hand testing to show how work system in different situations<br/>
$\color{#FF0000}{{DELETE}}$ /api/analytics/delete/{id} - Delete analytics data by ID<br/>
$\color{#E3C678}{{POST}}$ /api/analytics/createDataForTestSystemInVideo - Create data set<br/>

## Build with
* [![Spring][Spring]][Spring-url]
* [![Docker][Docker]][Docker-url]
* [![OpenJDK][OpenJDK]][Docker-url]
* [![POSTGRESQL][POSTGRESQL]][POSTGRESQL-url]
* [![REACT][REACT]][REACT-url]
* [![TS][TS]][TS-url]
* [![HTML][HTML]][HTML-url]
* [![CSS][CSS]][CSS-url]

## Preview
### Get all analytics
#### 1. Postman
![image](https://github.com/DaniilZotin/Full-Stack-Analytics/assets/85665335/afda41af-d478-475b-9e4b-ac32a7c28066)
#### 2. App
![image](https://github.com/DaniilZotin/Full-Stack-Analytics/assets/85665335/d611a272-b768-45f4-a212-b8c7f434cf79)


### Get all analytics when DB do not has advertisement
#### 1. Postman
![image](https://github.com/DaniilZotin/Full-Stack-Analytics/assets/85665335/49d0d9bc-e0b8-4262-b54b-63e3884c9f2b)
#### 2. App
![image](https://github.com/DaniilZotin/Full-Stack-Analytics/assets/85665335/1c78768a-9f8f-43a1-9e20-40dcdf0648e0)

### Inside information about advertisement
![image](https://github.com/DaniilZotin/Full-Stack-Analytics/assets/85665335/9d0c42b6-5d29-428c-9c9d-6684cca43ddf)

### Home page
![image](https://github.com/DaniilZotin/Full-Stack-Analytics/assets/85665335/8af54fee-f6d3-4268-8ec1-a6d53434f98d)

### About page
![image](https://github.com/DaniilZotin/Full-Stack-Analytics/assets/85665335/95456036-bdde-4e5a-98a0-4f67974b16f7)

### Error page
![image](https://github.com/DaniilZotin/Full-Stack-Analytics/assets/85665335/dcd0ca3f-e488-4c6d-848b-c0f18bc13508)


## Set up
### 1. Clone the repo of backend
```sh
    https://github.com/DaniilZotin/Back-end-Spring-Analytics.git
```
### 2. Up Docker
```sh
     docker-compose up --build
```
### 3. You can use port 8094 to check app in postman
### 4. Clone the repo of frontend
```sh
    https://github.com/DaniilZotin/Front-end-React-Analytics.git
```
### 5. Build project(frontend)
### 6. Start app
```sh
    npm start
```































[Spring]: https://img.shields.io/badge/Spring-6DB33F?style=for-the-badge&logo=spring&logoColor=white
[Spring-url]: https://spring.io/projects/spring-framework

[Docker]: https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white
[Docker-url]: https://www.docker.com/

[OpenJDK]: https://img.shields.io/badge/OpenJDK-000000?style=for-the-badge&logo=openjdk&logoColor=white
[OpenJDK-url]: https://www.docker.com/

[POSTGRESQL]: https://img.shields.io/badge/postgresql-4169E1?style=for-the-badge&logo=postgresql&logoColor=white
[POSTGRESQL-url]: https://www.docker.com/

[REACT]: https://img.shields.io/badge/react-61DAFB?style=for-the-badge&logo=react&logoColor=black
[REACT-url]: https://www.docker.com/

[TS]: https://img.shields.io/badge/typescript-3178C6?style=for-the-badge&logo=typescript&logoColor=white
[TS-url]: https://www.docker.com/

[HTML]: https://img.shields.io/badge/html-E34F26?style=for-the-badge&logo=HTML5&logoColor=white
[HTML-url]: https://www.docker.com/

[CSS]: https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=CSS3&logoColor=white
[CSS-url]: https://www.docker.com/

