<h1 align="center">
  Challenge Bravo
  <br />
</h1>

<p align="center">

<p align="center">
  <img alt="Challenge Bravo CI" src="https://github.com/diegodiogenes/challenge-bravo/actions/workflows/fastapi.yml/badge.svg" />
  <img alt="codecov" src="https://codecov.io/gh/diegodiogenes/challenge-bravo/branch/main/graph/badge.svg?token=1IV9SPU796" />
  <img alt="GitHub top language" src="https://img.shields.io/github/languages/top/diegodiogenes/challenge-bravo?style=plastic" />
  <img alt="GitHub language count" src="https://img.shields.io/github/languages/count/diegodiogenes/challenge-bravo?style=plastic" />
  <img alt="GitHub last commit" src="https://img.shields.io/github/last-commit/diegodiogenes/challenge-bravo?style=plastic" />
</p>


## About the Project

Currency rate api, developed to challenge bravo. All that currencies rate has base with USD.


## Technology

This project was developed with the following technologies:

- [Python](https://www.python.org/)
- [FastAPI](https://fastapi.tiangolo.com/)
- [Docker](https://www.docker.com/)


## Getting Started

### Prerequisites

- [Docker](https://www.docker.com/)
- [Docker Compose](https://docs.docker.com/compose/)


### Install and Run

1. Clone the repository:
```bash
git clone https://github.com/diegodiogenes/challenge-bravo.git
```
2. Build Project:
```bash
docker-compose build --no-cache
```
3. Run:
```bash
docker-compose up
```
4. Access on your localhost:
```
http://localhost:8030/docs
```
5. Enjoy it!
6. Clear database and update new instance:
```
docker-compose down -v
```
7. Run tests:
```
docker-compose exec api pytest .
```

## How to contribute

Contributions are what make the open source community such an amazing place to be learn, inspire, and create. Any contributions you make are **greatly appreciated**.

1. Fork the Project.
2. Create your Feature Branch `git checkout -b feat/my-feature`.
3. Commit your Changes `git commit -m 'feat: My new feature'`.
4. Push to the Branch `git push origin feat/my-feature`.
5. Open a Pull Request.

After the merge of your pull request is done, you can delete your branch.


## License

Distributed under the MIT License. See [LICENSE](LICENSE) for more information.

---

Made with ♥ by [Wesley Mendes](https://wesleymendes.com.br/) :wave: