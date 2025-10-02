# MentalHelp
O MentalHelp é um app onde alunos entram com gov.br para ter apoio seguro. Eles podem conversar com outros alunos ou com psicólogos verificados, fortalecendo autoestima e relações sociais. Há botão de denúncia para proteger os usuários, e a escola pode acessar matrícula e mensagens em casos necessários.

## Funcionalidades:

- Conexão entre alunos e psicólogos
- Chat seguro para conversas, entre alunos, seus colegas e psicólogos

## Funcionalidades:

- Frontend: Visual Code
- Backend: Node.js + Express
- Banco de Dados: SQLite (Prisma)
Here's a quick public tour of Open Library to get you familiar with the service and its offerings (10min).

## ## Instalação

git clone https://github.com/YumaLord/mentalhelp.git
cd mentalhelp
npm install
npm start


Run `docker compose up` and visit http://localhost:8080

Need more details? Checkout the [Docker instructions](https://github.com/internetarchive/openlibrary/blob/master/docker/README.md)
or [video tutorial](https://archive.org/embed/openlibrary-developer-docs/openlibrary-docker-set-up.mp4).

***Alternatively***, if you do not want to set up Open Library on your local computer, try Gitpod!
This lets you work on Open Library entirely in your browser without having to install anything on your personal computer.
Warning: This integration is still experimental.
[![Open In Gitpod](https://img.shields.io/badge/Contribute%20with-Gitpod-908a85?logo=gitpod)](https://gitpod.io/#https://github.com/internetarchive/openlibrary/)

### Developer's Guide

You can also find more information regarding Developer Documentation for Open Library in the Open Library [Wiki](https://github.com/internetarchive/openlibrary/wiki/).

## Code Organization

* openlibrary/core - core openlibrary functionality, imported and used by www
* openlibrary/plugins - other models, controllers, and view helpers
* openlibrary/views - views for rendering web pages
* openlibrary/templates - all the templates used in the website
* openlibrary/macros - macros are like templates, but can be called from wikitext

## Architecture

### The Backend

OpenLibrary is developed on top of the Infogami wiki system, which is itself built on top of the web.py Python web framework and the Infobase database framework.

- [Overview of Backend Web Technologies](https://openlibrary.org/about/tech)

Once you've read the overview of OpenLibrary Backend technologies, it's highly encouraged you read the developer primer which explains how to use Infogami (and its database, Infobase).

- [Infogami Developer Tutorial](https://openlibrary.org/dev/docs/infogami)

If you want to dive into the source code for Infogami, see the [Infogami repo](https://github.com/internetarchive/infogami).

## Running tests

Open Library tests can be run using docker. Kindly look up on our [Testing Document](https://github.com/internetarchive/openlibrary/wiki/Testing) for more details.

```
docker compose run --rm home make test
```

## Contributing

There are many ways volunteers can contribute to the Open Library project, from development and design to data management and community engagement. Here’s how you can get involved:

### Developers
- **Getting Started:** Check out our [Contributing Guide](https://github.com/internetarchive/openlibrary/blob/master/CONTRIBUTING.md) for instructions on how to set up your development environment, find issues to work on, and submit your contributions.
- **Good First Issues:** Browse our [Good First Issues](https://github.com/internetarchive/openlibrary/issues?q=is%3Aissue+is%3Aopen+-linked%3Apr+label%3A%22Good+First+Issue%22+no%3Aassignee) to find beginner-friendly tasks.

### Designers
- **Design Contributions:** We welcome designers to help improve the user experience. You can start by looking at [design-related issues](https://github.com/internetarchive/openlibrary/labels/design).

### Librarians and Data Enthusiasts
- **Data Contributions:** Learn how to contribute to our catalog and help improve book data on Open Library. Visit our [volunteer page](https://openlibrary.org/volunteer) for more information.

### Community Engagement
- **Join our Community Calls:** Open Library hosts weekly community and design calls. Check the [community call schedule](https://github.com/internetarchive/openlibrary/wiki/Community-Call) for times and details.
- **Ask Questions:** If you have any questions, request an invitation to our Slack channel on our [volunteers page](https://openlibrary.org/volunteer).

For more detailed information, refer to the [Contributing Guide](https://github.com/internetarchive/openlibrary/blob/master/CONTRIBUTING.md).


## License

All source code published here is available under the terms of the [GNU Affero General Public License, version 3](https://www.gnu.org/licenses/agpl-3.0.html).
