<div id="top"></div>

<p align="center">
    <a href="https://github.com/nelsonacos/simple-wordpress-up/graphs/contributors">
        <img src="https://img.shields.io/github/contributors/nelsonacos/simple-wordpress-up.svg?style=for-the-badge" alt="GitHub contributors">
    </a>
    <a href="https://github.com/nelsonacos/simple-wordpress-up/issues">
        <img src="https://img.shields.io/github/issues/nelsonacos/simple-wordpress-up?style=for-the-badge" alt="GitHub issues">
    </a>
    <a href="https://github.com/tu-usuario/simple-wordpress-up/network">
        <img src="https://img.shields.io/github/forks/nelsonacos/simple-wordpress-up?style=for-the-badge" alt="GitHub forks">
    </a>
    <a href="https://github.com/tu-usuario/simple-wordpress-up/stargazers">
        <img src="https://img.shields.io/github/stars/nelsonacos/simple-wordpress-up?style=for-the-badge" alt="GitHub stars">
    </a>
    <a href="https://github.com/nelsonacos/simple-wordpress-up/blob/main/LICENSE">
        <img src="https://img.shields.io/github/license/nelsonacos/simple-wordpress-up?style=for-the-badge" alt="GitHub license">
    </a>
</p>

<br />
<div align="center">
  <p align="center">
    <br />
    <br />
    <a href="#"><strong>Explore the documentation</strong></a>
    <br />
    <br />
    <a href="#">View Demo</a>
    ·
    <a href="https://github.com/nelsonacos/simple-wordpress-up/issues">Report a Bug</a>
    ·
    <a href="https://github.com/nelsonacos/simple-wordpress-up/issues">Request a Feature</a>
  </p>
</div>
<br />

## Getting Started

1. Clone the repository

```sh
git clone https://github.com/nelsonacos/simple-wordpress-up.git
```

2. Open the command line and navigate to the project folder

```sh
cd simple-wordpress-up
```
2. Create the `.env` file to configure the environment variables

```sh
# Unix System
cat .env.example > .env

# Windows System
copy .env.example .env
```
3. Configure environment variables

```sh
# Database Configuration
MYSQL_ROOT_PASSWORD=supersecurepassword
MYSQL_DATABASE=wordpress
MYSQL_USER=wp_user
MYSQL_PASSWORD=securepassword

# WordPress Settings
WORDPRESS_DB_HOST=db
WORDPRESS_DB_USER=wp_user
WORDPRESS_DB_PASSWORD=securepassword
WORDPRESS_DB_NAME=wordpress
```

5. Starting the Project with Docker Compose

```sh
docker-compose up -d --build
```
Open http://localhost:8080/ with your browser to see the result.

## Contribution

If you want to contribute to this project, follow these steps:

1. Fork the project
2. Create a branch for your contribution (git checkout -b feature/AmazingFeature)
3. Make the necessary changes
4. Commit your changes (git commit -m 'Add some amazing feature')
5. Push your branch (git push origin feature/AmazingFeature)
6. Open a Pull Request in this repository

<p align="right">(<a href="#top">back to top</a>)</p>