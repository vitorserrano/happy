<p align="center">
  <img src=".github/logo.svg" alt="Happy" />
</p>

<p align="center">
  <b>Conecte pessoas a orfanatos e traga felicidade as crianças.</b>
</p>

## Conteúdo

- [Database](#database)
- [Server](#server)
- [Web](#web)
- [Mobile](#mobile)

<a id="server"></a>

## 📃 Server

<a id="web"></a>

## 🖥 Web

Na aplicação Web vamos utilizar o framework **ReactJS** com o template Typescript, para isso vamos iniciar nosso projeto com o seguinte comando:

```sh
  yarn create react-app web --template typescript
```

<details><summary>Dependências</summary>
<p>

### react-icons

O **React Icons** irá nos ajudar na utilização de ícones na aplicação web. Esse pacote é bem completo e conta com várias coleções de ícones fomosas como **Font Awesome**, **Feather Icons**, **Meterial Icons**, entre outros....

1. Primeiro vamos instalar a dependência:

```sh
  $ yarn add react-icons
```

2. Para usar é bem simples, vamos importar esse pacote no arquivo onde queremos adicionar os ícones. Note que após 'react-icons' é passado uma '/' e após essa barra você irá informar qual coleção de ícones irá utilizar. Por fim, pasta criar o component com o nome do ícone que você importou.

```javascript
  // Importação
  import { FiArrowLeft } from 'react-icons/fi'

  // Component
  <FiArrowLeft
```

### react-router-dom

- O **React Router DOM** será responsável pelo roteamento da nossa aplicação web. Para isso vamos fazer sua instalação e em seguida instalar sua tipagem.

```sh
  # Instalação do react-router-dom
  $ yarn add react-router-dom

  # instalação do react-router-dom com tipagem para TypeScript
  $ yarn add @types/react-router-dom -D
```

### leaflet

- Para manusearmos um mapa nós vamos utilizar o **Leaflet**. O **Leaflet** é uma alternativa open source para utilização de mapas com **javascript**. Para utilizarmos vamos precisar instalar o seu próprio pacote, o pacote para **ReactJS** e também o pacote de tipagems

```sh
  # Instalação do leaflet e react-leaflet
  $ yarn add leaflet react-leaflet

  # instalação do react-leaflet com tipagem para TypeScript
  $ yarn add @types/react-leaflet -D
```

</p>
</details>

<a id="mobile"></a>

## :iphone: Mobile
