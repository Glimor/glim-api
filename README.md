
<p align="center">
  <img src="https://i.ibb.co/bKj5Dvk/glim.png" alt="Glim API Banner">
</p>

## Overview

  

**Glim API** is a powerful and flexible dynamic API generator designed to simplify the creation of RESTful APIs with FastAPI. With built-in authentication, rate limiting, and localization, Glim API provides a robust framework tailored to meet diverse needs. Configure everything easily with a `config.toml` file, making setup quick and painless.

  

> **Note:** Glim API is currently under active development. You might encounter some bugs or incomplete features. We appreciate your feedback and contributions to help improve the project!

  

## 🚀 Features

  

-  **Dynamic API Generation**: Effortlessly generate CRUD APIs based on your custom models.

-  **🔐 JWT Authentication**: Secure your API endpoints with JSON Web Token (JWT) authentication.

-  **⚡ Rate Limiting**: Manage and control API usage with configurable rate limiting options.

-  **🌍 Localization**: Support for multiple languages and currencies, making your API globally accessible.

-  **💾 Flexible Database Integration**: Seamless integration with MongoDB or a simple local database.

  

## 🛠 Installation

  

To install Glim API, run the following command:

  

`pip install glimapi`

  
  

### ⚙️ Configuration

  

Once installed, you can generate a `config.toml` file by running the following command:

  

`glimapi-generate-toml`

  

This command will create a `config.toml` file in your project directory which holds all the configuration settings for Glim API, allowing for extensive customization.

  

Additionally, the command will also generate a `middlewares` directory in your project root. You can add your custom middleware files to this directory to extend or modify the functionality of Glim API.

  

### Customizing `config.toml`

  

-  **Database Settings**: Choose between MongoDB or a local database; set up connection details accordingly.

-  **Server Settings**: Define the host and port settings for FastAPI.

-  **JWT Authentication**: Configure JWT parameters, including secret keys and token expiration.

-  **Caching**: Enable Redis caching and specify connection details.

-  **Rate Limiting**: Set limits on the number of requests allowed per minute.

-  **Models**: Define your API models, including fields, filters, and relationships.

  

## 💻 Usage

  

### Starting the Glim API

  

Kickstart your API with a single command:

  

`glimapi-start`

  

### Help Command

  

Need assistance? Access the help command:

  

`glimapi-help`

  

### Generate Configuration File

  

Regenerate or create the `config.toml` file with:

  

`glimapi-generate-toml`

  

## 🛠️ Future Enhancements and Roadmap

  

We have exciting features planned for the future! Here’s what we’re working on:

  

- [ ] **Automated Docker Setup**: Simplify deployment with an out-of-the-box Docker configuration.

- [ ] **GraphQL Support**: Add support for GraphQL endpoints in addition to REST.

- [ ] **Enhanced Logging**: Implement a more robust logging system for better debugging and monitoring.

- [ ] **OAuth2 Authentication**: Integrate OAuth2 as an alternative authentication method.

- [ ] **Automated Tests**: Create a comprehensive test suite to ensure reliability and stability.

- [ ] **WebSocket Support**: Enable real-time communication with WebSocket integration.

- [ ] **Multi-Database Support**: Add support for additional databases like PostgreSQL and MySQL.

- [ ] **API Versioning**: Introduce API versioning to manage breaking changes.

- [ ] **Improved Documentation**: Expand the documentation with detailed examples and use cases.

- [ ] **Localization Enhancements**: Extend localization support to include more languages and regions.

- [ ] **Automated Diagram Generation**: Automatically generate architecture and entity-relationship diagrams based on the API models and configurations.

- [ ] **Swagger Integration**: Provide automatic API documentation using Swagger UI, making it easy to explore and test API endpoints.
- [ ] **Custom View Integration**: Allow users to manually add custom views to extend the functionality of the API.

  
  

## 📜 License

  

This project is licensed under the **CC BY-NC-SA 4.0 License**.

  

- 🛑 **NonCommercial**: You may not use this project for commercial purposes.

- 🚫 **No Derivatives**: You may not modify, distribute, or sublicense the code without permission.

- 🎓 **Personal and Educational Use**: The project is intended for personal and educational use only.

  

For more details, please refer to the [LICENSE](LICENSE) file.

  

## Support the Project

  

If you like this project and want to support its development, consider buying me a coffee!

  

[![Buy Me A Coffee](https://cdn.buymeacoffee.com/buttons/v2/default-yellow.png)](https://www.buymeacoffee.com/glimor)

## Contributors
This project is built and maintained by a community of dedicated individuals. As of now, there are no contributors, but we're excited to see who will be the first to join our journey!

### Hows to Contribute

1. **Fork the Repository**: Start by forking the repository to your GitHub account.
2. **Create a New Branch**: Work on your changes in a new branch.
3. **Make Changes**: Whether it's a new feature, bug fix, or documentation improvement, every contribution is valuable.
4. **Submit a Pull Request**: When your changes are ready, submit a pull request for review.

<div style="text-align: center; margin-top: 40px;">
  <h2>🎉 Your Name Could Be Here Next!</h2>
  <img src="https://github.com/glimor.png" width="120" height="120" style="border-radius: 50%; margin-top: 10px; border: 2px solid #ed771c;" alt="Glimor"/>
  <p style="font-size: 1.2em; margin-top: 10px;"><strong>Glimor</strong></p>
</div>


---

Looking forward to seeing your contributions and growing this project together!