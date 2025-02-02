# SoC-Portal

### Official repository for the SoC Portal Project created by TTY17

#### This repository is a part of HelloFOSS '24

An on-going project of the Web and Coding Club. Built using Django REST Framework and React.

# Getting Started

To learn the usage of this repository and begin contributing go to the **Usage** section of [CONTRIBUTING.md](CONTRIBUTING.md)


# Documentation

## Frontend

This project generates documentation using [StoryBook](https://www.npmjs.com/package/@storybook/react). Make sure that you add JSDoc comments for the components. To access the documentation, run the following commands on your terminal:

```bash
# installation
npm install --save-dev @storybook/react
# configuration
npx sb init
# to view the documentation
npx storybook
```

## Backend

### API Documentation
The project generates API documentation using [drf-yasg](https://github.com/axnsan12/drf-yasg), provided through Swagger and ReDoc. To access the API documentation, follow these steps:

Open a web browser and navigate to one of the following endpoint:

```bash
http://127.0.0.1:8000/redoc
http://127.0.0.1:8000/swagger
```

### Code Documentation
The documentation for the back-end source code is automatically generated by Sphinx. You can access it using the backend/docs/_build/html/index.html as an entry-point (open it on the browser).

Whenever you make any changes in the code, before making a pull request make sure you run the following commands to generate documentation for the changes you have made.

```shell
cd backend/docs
./make.bat html
```
# Contributing

Check out [CONTRIBUTING.md](CONTRIBUTING.md) for guidelines on contributing to the repo.
