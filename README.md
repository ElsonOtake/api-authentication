<a name="readme-top"></a>

<!-- TABLE OF CONTENTS -->

# 📗 Table of Contents

- [📖 About the Project](#about-project)
  - [🛠 Built With](#built-with)
    - [Tech Stack](#tech-stack)
    - [Key Features](#key-features)
  - [🚀 Live Demo](#live-demo)
- [💻 Getting Started](#getting-started)
  - [Setup](#setup)
  - [Prerequisites](#prerequisites)
  - [Install](#install)
  - [Usage](#usage)
  - [Run tests](#run-tests)
- [👥 Author](#author)
- [🔭 Future Features](#future-features)
- [🤝 Contributing](#contributing)
- [⭐️ Show your support](#support)
- [🙏 Acknowledgements](#acknowledgements)
- [📝 License](#license)

<!-- PROJECT DESCRIPTION -->

# 📖 API Authentication <a name="about-project"></a>

**API authentication** is an information-sharing project related to API authentication. The data from this application supports the [article created on Medium](https://medium.com/@elsonotake/add-authentication-to-your-rails-api-application-8fd811f4a1a8) with API authentication tips.

## 🛠 Built With <a name="built-with"></a>

### Tech Stack <a name="tech-stack"></a>

<details>
  <summary>Server</summary>
  <ul>
    <li><a href="https://rubyonrails.org/">Ruby on Rails</a></li>
    <li><a href="https://github.com/rspec/rspec-rails">RSpec Rails</a></li>
    <li><a href="https://github.com/rswag/rswag">Rswag</a></li>
    <li><a href="https://jwt.io/">JWT</a></li>
    <li><a href="https://github.com/bcrypt-ruby/bcrypt-ruby">bcrypt</a></li>
  </ul>
</details>

<details>
<summary>Database</summary>
  <ul>
    <li><a href="https://www.sqlite.org/">SQLite</a></li>
  </ul>
</details>

<!-- Features -->

### Key Features <a name="key-features"></a>

- **Basic API application**
- **CRUD**
- **Documentation using Rswagger**
- **API Authentication**
- **Authentication using token**

<p align="right">(<a href="#readme-top">back to top</a>)</p>

<!-- LIVE DEMO -->

## 🚀 Live Demo <a name="live-demo"></a>

> Add a link to your deployed project.

- [Live Demo Link]()

<p align="right">(<a href="#readme-top">back to top</a>)</p>

<!-- GETTING STARTED -->

## 💻 Getting Started <a name="getting-started"></a>

To get a local copy up and running, follow these steps.

### Prerequisites

In order to run this project you need:

[Ruby](https://www.ruby-lang.org/en/)

### Setup

Clone this repository to your desired folder:

using HTTPS:
```sh
  git clone https://github.com/ElsonOtake/api-authentication.git
  cd api-authentication
```

using an SSH key:
```sh
  git clone git@github.com:ElsonOtake/api-authentication.git
  cd api-authentication
```

using GitHub CLI:
```sh
  git clone gh repo clone ElsonOtake/api-authentication
  cd api-authentication
```

### Install

Install this project with:

```sh
  bundle install
````

Create the database:
```sh
  rails db:create db:migrate
```

### Usage

To run the project, execute the following command:

```sh
  rails server
```

### Run tests

To generate the [API documentation](http://localhost:3000/api-docs/index.html):

```sh
  rake rswag
```

<p align="right">(<a href="#readme-top">back to top</a>)</p>

<!-- AUTHORS -->

## 👥 Author <a name="author"></a>

👤 **Elson Otake**

- GitHub: [elsonotake](https://github.com/elsonotake)
- Twitter: [@elsonotake](https://twitter.com/elsonotake)
- LinkedIn: [elsonotake](https://linkedin.com/in/elsonotake)

<p align="right">(<a href="#readme-top">back to top</a>)</p>

<!-- FUTURE FEATURES -->

## 🔭 Future Features <a name="future-features"></a>

- [ ] **Documentation of login via API**
- [ ] **Documentation of authentication using token**
- [ ] **Documentation of protected endpoints**

<p align="right">(<a href="#readme-top">back to top</a>)</p>

<!-- CONTRIBUTING -->

## 🤝 Contributing <a name="contributing"></a>

Contributions, issues, and feature requests are welcome!

Feel free to check the [issues page](../../issues/).

<p align="right">(<a href="#readme-top">back to top</a>)</p>

<!-- SUPPORT -->

## ⭐️ Show your support <a name="support"></a>

Give a ⭐️ if you like this project!

<p align="right">(<a href="#readme-top">back to top</a>)</p>

<!-- ACKNOWLEDGEMENTS -->

## 🙏 Acknowledgments <a name="acknowledgements"></a>

I would like to thank...

- [Microverse](https://www.microverse.org/)
- [Postman](https://www.postman.com/)

<p align="right">(<a href="#readme-top">back to top</a>)</p>

<!-- LICENSE -->

## 📝 License <a name="license"></a>

This project is [MIT](./MIT.md) licensed.

<p align="right">(<a href="#readme-top">back to top</a>)</p>
