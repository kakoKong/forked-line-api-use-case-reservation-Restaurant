# Overview

This is the demo app source code for [Restaurant reservation](https://lineapiusecase.com/en/usecase/reservation.html) provided on the [LINE API Use Case site](https://lineapiusecase.com/en/top.html). By referring to the steps described in this article, you can develop a restaurant reservation app using the LINE API.

The Restaurant Reservation app can be launched on the LIFF browser with the LINE app and allows you to make restaurant reservations. To prevent users from forgetting to visit the store, a reminder function via LINE message can be implemented by default.

# Libraries

## Node.js

Install Node.js, which will be used for the front-end development, in your local development environment.  
*We recommend installing the latest LTS version of v10.13 or higher

Node.js download site:

https://nodejs.org/en/download/

## Python

Install Python version 3.8 or later if it isn't already installed.

You can check if it's installed by entering this command in Command Prompt or Terminal:

```
python --version
```

If Python is installed, the version will be returned. For example:

```
Python 3.8.3
```

Install Python (3.8 or higher), used for back-end development, in your local development environment if it's not already installed.

Python installation reference site:

Windows: https://docs.python.org/3/using/windows.html  
Mac: https://docs.python.org/3/using/mac.html

## AWS SAM

The AWS Serverless Application Model (AWS SAM) is used to deploy this app.

See the [official AWS documentation](https://docs.aws.amazon.com/serverless-application-model/latest/developerguide/serverless-sam-cli-install.html) to register and set up an AWS account, and install the AWS SAM CLI and Docker.  

*Recommended version of SAM CLI is 1.15.0 or later.  
*Docker installation is also required, with or without local testing.

### Reference points in the official documentation

Complete these items in the official documentation and proceed to the next step. If you have already installed it, you can skip this section.

*This document was created in December 2020 and may be inconsistent with the latest official documentation.

1. Install AWS SAM CLI
1. Set up AWS authentication credentials
1. (Optional) Tutorial: Deploying the Hello World app

# Getting Started / Tutorial

This procedure explains how to create a LINE channel, build the backend and frontend, and check the operation, which are necessary for app development.

See these steps to build your local and production (AWS) environment:

- **[Create a LINE channel](docs/en/liff-channel-create.md)**
- **[Build the back-end](docs/en/back-end-construction.md)**
- **[Build front end production environment (AWS)](docs/en/front-end-construction.md)**
- **[Build a local front end environment](docs/en/front-end-development-environment.md)**
***
- **[Test data input](docs/en/test-data-charge.md)**
***
- **[Check operation](docs/en/validation.md)**
***

# License

All files on Restaurant are free to use without conditions.

Download and clone to start developing apps using LINE API.

See [LICENSE](LICENSE) for details. (English)

# How to contribute

Thank you for taking the time to contribute. LINE API Use Case Restaurant isn't different from any other open source projects. You can help by:

- Filing an issue in [the issue tracker](https://github.com/line/line-api-use-case-reservation-restaurant/issues) to report bugs and propose new features and improvements.
- Asking a question using [the issue tracker](https://github.com/line/line-api-use-case-reservation-restaurant/issues).
- Contributing your work by submitting [a pull request](https://github.com/line/line-api-use-case-reservation-restaurant/pulls).

When you are sending a pull request, be aware of and accepting the following:

- Grant [the same license](LICENSE) to the contribution
- Represent the contribution is your own creation
- Not expected to give support for your contribution
