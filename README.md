<h1 align="center">Loïck Balloy</h1>

<p align="center">
  <b>Software Engineer · C++17 &amp; Python</b><br>
  Back-end, low-latency and ML systems whose correctness can be checked.
</p>

<p align="center">
  <img alt="Open to roles in Geneva, Lausanne, Zurich, Paris" src="https://img.shields.io/badge/open_to-Geneva_%C2%B7_Lausanne_%C2%B7_Zurich_%C2%B7_Paris-1f883d?style=flat-square">
  <img alt="Available February 2027" src="https://img.shields.io/badge/available-February_2027-0969da?style=flat-square">
  <a href="https://www.linkedin.com/in/loick-balloy-332708203/"><img alt="LinkedIn" src="https://img.shields.io/badge/LinkedIn-Lo%C3%AFck_Balloy-0a66c2?style=flat-square"></a>
  <a href="mailto:loick.balloy@epita.fr"><img alt="Email" src="https://img.shields.io/badge/email-loick.balloy%40epita.fr-59636e?style=flat-square"></a>
</p>

- **Now:** Software Engineering Intern at Renault Group (Ampere), Battery & Power Electronics Test Methods team. I built a Python code generator (LLM-assisted, intermediate representation, AST validation) that cut test bench program creation from several hours to under 5 minutes.
- **Education:** EPITA, Master's-level engineering degree (CTI-accredited), Security & Embedded Systems major, January 2027.
- **Looking for:** software engineering roles in finance or tech consulting, from February 2027. EU citizen.

## Selected projects

### [Order Book & Matching Engine](https://github.com/loickballoy/order_book) · C++17

Single-instrument limit order book: price-time priority, GTC and IOC orders, cancel by ID. Conservation and index-consistency invariants are checked by randomized tests on every benchmark run.

<a href="https://github.com/loickballoy/order_book#benchmarks-v2">
  <picture>
    <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/loickballoy/order_book/main/docs/bench-dark.svg">
    <img alt="Mean latency per order: 0.21 µs at 100 price levels up to 0.57 µs at 100,000" src="https://raw.githubusercontent.com/loickballoy/order_book/main/docs/bench-light.svg" width="100%">
  </picture>
</a>

### [NBA Predictor](https://github.com/loickballoy/NBA_Predictor) · C++17, Python, GCP, Terraform · [live demo](https://loickballoy.github.io/NBA_Predictor/)

Neural network written from scratch in C++, retrained every week on Cloud Run and promoted only if it beats both the baseline and the production model. LLM-written explanations are rejected if they cite a number absent from the data. MAE 4 to 11 % lower than the baseline on 7 of 8 stats.

<a href="https://loickballoy.github.io/NBA_Predictor/">
  <img alt="Projection page of the NBA Predictor demo" src="https://raw.githubusercontent.com/loickballoy/NBA_Predictor/main/docs/screenshots/dark.png" width="100%">
</a>

### [aniBet](https://github.com/loickballoy/aniBet) · Python, FastAPI, PostgreSQL

Prediction-market backend with a virtual currency. Bet placement and settlement run as atomic PL/pgSQL functions with row-level locks on balances. 125 pytest tests run in CI against a real PostgreSQL.

<a href="https://loickballoy.github.io/aniBet/">
  <img alt="AniBet Home Page" src="https://raw.githubusercontent.com/loickballoy/aniBet/main/docs/screenshots/home.png" width="100%">
</a>

## Stack

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://skillicons.dev/icons?i=cpp,py,postgres,fastapi,gcp,terraform,docker,githubactions,linux&theme=dark">
  <img alt="C++, Python, PostgreSQL, FastAPI, GCP, Terraform, Docker, GitHub Actions, Linux" src="https://skillicons.dev/icons?i=cpp,py,postgres,fastapi,gcp,terraform,docker,githubactions,linux&theme=light">
</picture>
