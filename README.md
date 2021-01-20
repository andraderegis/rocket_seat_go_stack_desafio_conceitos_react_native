![GoStack](https://storage.googleapis.com/golden-wind/bootcamp-gostack/header-desafios-new.png)

<h2 align="center">GoStack - Desafio Conceitos do React Native</h2>

# Sobre

**Este projeto se trata de uma simples aplicação React Native desenvolvida como desafio da Fase 1 do curso [GoStack](https://pages.rocketseat.com.br/gostack), ministrado pela [RocketSeat](https://rocketseat.com.br/)**

# Instruções

**Antes de executar a aplicação, é necessário configurar o ambiente para a execução da mesma. A RocketSeat disponibilizou um excelente passo a passo que pode ser acessado [clicando aqui](https://react-native.rocketseat.dev/).**

**Após a configuração do ambiente, também é nessário o uso do container docker responsável pelo back-end. A seguir, execute o seguinte comando para baixar a imagem:**

```
docker pull andradereginaldo/go_stack_desafio_backend_nodejs
```

**Para executar o container execute o seguinte comando:**

```
docker run -p 3333:3333 andradereginaldo/go_stack_desafio_backend_nodejs
```

**Na utilização do emulador Android, é necessário fazer um redirecionamento, para que a aplicação consiga comunicar com o back-end local, executado por meio do docker. Execute o seguinte comando:**

```
adb reverse tcp:3333 tcp:3333
```

**Inicialize o ambiente React Native, executando o seguinte comando:**

```
yarn start
```

**Uma vez com o container da aplicação back-end em execução e o react native em execução, execute o seguinte comando dentro do diretório da aplicação ReactJS:**

- **Android**

```
yarn android
```

- **iOS**

```
yarn ios
```

# Testes Funcionais

**Para a execução dos testes das rotas da API, dentro do diretório da aplicação, execute o seguinte comando:**

```
yarn test
```

</br>

<p align="center">
  <img alt="GitHub language count" src="https://img.shields.io/github/languages/count/andraderegis/rocket_seat_go_stack_desafio_conceitos_reactjs?color=%2304D361">

  <img alt="License" src="https://img.shields.io/badge/license-MIT-%2304D361">

  <a href="https://github.com/andraderegis/rocket_seat_go_stack_desafio_conceitos_reactjs/stargazers">
    <img alt="Stargazers" src="https://img.shields.io/github/stars/andraderegis/rocket_seat_go_stack_desafio_backend_com_node_js?style=social">
  </a>
</p>
