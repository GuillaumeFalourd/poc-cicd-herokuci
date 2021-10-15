# poc-cicd-herokuci

Poc of a factorial app for the building CI/CD workflow with Heroku CI using [this article](https://dev.to/mwanjemike/build-a-ci-cd-pipeline-with-heroku-ci-3de9) (won't work if no billing method registered on Heroku).

## How to run

Run `npm start` at the repository `root` directory, then access the endpoints on your navigator (e.g: `http://localhost:3000/`)


## How to test

Run `npm test` at the repository `root` directory:

```bash
> cicd-with-herokuci@1.0.0 test
> mocha *.test.js || true



  Factorial test
    ✔ Factorial(0) = 1
    ✔ Factorial(1) = 1
    ✔ Factorial(5) = 120
    ✔ Factorial(171) = Infinity


  4 passing (7ms)
```