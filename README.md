[![Contributors][contributors-shield]][contributors-url]
[![Forks][forks-shield]][forks-url]
[![Stargazers][stars-shield]][stars-url]
[![Issues][issues-shield]][issues-url]


<!-- PROJECT LOGO -->
<br />
<p align="center">
  <h3 align="center">atlassian/confluence-server</h3>

  <p align="center">
    Docker setup for confluence-server
    <br />
    <br />
    ·
    <a href="https://github.com/beuluis/atlassian-confluence-server/issues">Report Bug</a>
    ·
    <a href="https://github.com/beuluis/atlassian-confluence-server/issues">Request Feature</a>
  </p>
</p>

<!-- ABOUT THE PROJECT -->
## About The Project

Small docker setup for confluence-server. The production environment also uses [jwilder/nginx-proxy](https://github.com/nginx-proxy/nginx-proxy) and [nginx-proxy/docker-letsencrypt-nginx-proxy-companion](https://github.com/nginx-proxy/docker-letsencrypt-nginx-proxy-companion).

<!-- GETTING STARTED -->
## Getting Started Local

To get a local copy up and running follow these simple example steps.

### Prerequisites

* [Docker](https://docs.docker.com/get-docker/)
* [Docker Compose](https://docs.docker.com/compose/install/)

### Installation

1. Clone the repo
```sh
git clone https://github.com/beuluis/atlassian-confluence-server.git
```
2. Start docker-compose
```sh
docker-compose up --build
```
3. Navigate to `localhost:8097`
4. Follow setup instructions

Local db login information:

DB: `atlassianConfluenceDev`

User: `atlassianConfluenceDev`

Password: `966VHT7SUcPnaqpJAz32fP`


### Production

The production environment is still being worked on. Under `docker-compose.production.yml` you can find an example for my setup. Feel free to fork it and change the setup for yourself

<!-- CONTRIBUTING -->
## Contributing

Contributions are what make the open source community such an amazing place to be learn, inspire, and create. Any contributions you make are **greatly appreciated**.

1. Fork the Project
2. Create your Feature Branch (`git checkout -b feature/AmazingFeature`)
3. Commit your Changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the Branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request


<!-- CONTACT -->
## Contact

Luis Beu - me@luisbeu.de


<!-- MARKDOWN LINKS & IMAGES -->
<!-- https://www.markdownguide.org/basic-syntax/#reference-style-links -->
[contributors-shield]: https://img.shields.io/github/contributors/beuluis/atlassian-confluence-server.svg?style=flat-square
[contributors-url]: https://github.com/beuluis/atlassian-confluence-server/graphs/contributors
[forks-shield]: https://img.shields.io/github/forks/beuluis/atlassian-confluence-server.svg?style=flat-square
[forks-url]: https://github.com/beuluis/atlassian-confluence-server/network/members
[stars-shield]: https://img.shields.io/github/stars/beuluis/atlassian-confluence-server.svg?style=flat-square
[stars-url]: https://github.com/beuluis/atlassian-confluence-server/stargazers
[issues-shield]: https://img.shields.io/github/issues/beuluis/atlassian-confluence-server.svg?style=flat-square
[issues-url]: https://github.com/beuluis/atlassian-confluence-server/issues
[license-shield]: https://img.shields.io/github/license/beuluis/atlassian-confluence-server.svg?style=flat-square