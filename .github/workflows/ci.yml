name: CI Pipeline

on:
  push:
    branches: [main]
pull_request:
  branches:[main]
jobs: 
build-and-test:
  runs-on:ubuntu-latest
  steps:
  -name: Baixar código
  uses: actions/chekout@v4

  -name: Instalar depências
  run:npm install

  - name:Rodar testes 
  run:npm test
