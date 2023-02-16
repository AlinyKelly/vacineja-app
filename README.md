<p align="center">
  <img alt="GitHub language count" src="https://img.shields.io/github/languages/count/alinykelly/vacineja-app?color=%2304D361">

  <img alt="Repository size" src="https://img.shields.io/github/repo-size/alinykelly/vacineja-app">
  
  <a href="https://github.com/alinykelly/vacineja-app/commits/master">
    <img alt="GitHub last commit" src="https://img.shields.io/github/last-commit/alinykelly/vacineja-app">
  </a>
    
   <img alt="License" src="https://img.shields.io/badge/license-MIT-brightgreen">
   <a href="https://github.com/alinykelly/vacineja-app/stargazers">
    <img alt="Stargazers" src="https://img.shields.io/github/stars/alinykelly/vacineja-app?style=social">
  </a>  
 
</p>
<h1 align="center">
    <img alt="Vacine Já" title="#Vacine Já - App" src="./client/public/assets/banner.png" />
</h1>

<h4 align="center"> 
	🚧  Vacine Já 💉 Versão Mobile em Construção 🚀 🚧
</h4>

<p align="center">
 <a href="#-sobre-o-projeto">Sobre</a> •
 <a href="#-funcionalidades">Funcionalidades</a> •
 <a href="#-layout">Layout</a> • 
 <a href="#-como-executar-o-projeto">Como executar</a> • 
 <a href="#-tecnologias">Tecnologias</a> • 
 <a href="#-contribuidores">Contribuidores</a> • 
 <a href="#-autor">Autor</a> • 
 <a href="#user-content--licença">Licença</a>
</p>


## 💻 Sobre o projeto

💉 Vacine Já - é uma plataforma de cadastro de vacinas e insumos que pode ser utilizada por Clínicas Médicas, Farmácias, Hospitais e até mesmo Clínicas Veterinárias.

Projeto desenvolvido durante o curso de **Análise e Desenvolvimento de Sistemas** oferecido pela [UNIFOR](https://www.unifor.br/).
O Projeto faz parte do Projeto de Conclusão de Curso que é dividido em 3 disciplinas, que são Projeto Aplicado a Desenvolvimento de Software, Projeto Aplicado a Plataforma Web e Projeto Aplicado a Plataforma Móveis.

---

## ⚙️ Funcionalidades

- [x] Empresas podem utilizar a plataforma web para:
  - [x] cadastrar insumos e vacinas
  - [x] controlar estoque
  - [x] realizar verificação de agendamentos
  - [x] visualizar dashboards e relatórios

- [x] As empresas tem acesso ao aplicativo móvel, onde podem:
  - [x] visualizar dashboards e relatórios

- [x] Pacientes podem utilizar a plataforma web para:
  - [x] verificar locais de vacinação
  - [x] agendar aplicações

- [x] Pacientes tem acesso ao aplicativo móvel, onde podem:
  - [x] navegar pelo mapa para ver as instituições cadastradas
  - [x] entrar em contato com a entidade através do E-mail ou do WhatsApp

---

## 🎨 Layout

O layout da aplicação está disponível no Figma:

<a href="https://www.figma.com/file/UKd0fLRvpYp9ijLfbMt1qR/Vacine-J%C3%A1---PADS-(Web)?node-id=5%3A16&t=14mkmnWg5YzYx0AM-1">
  <img alt="Made by Vacine já" src="https://img.shields.io/badge/Acessar%20Layout%20-Figma-%2304D361">
</a>

### Mobile

<p align="center">
  <img alt="Vacine Já" title="#Vacine Já" src="./client/public/assets/home-mobile.png" width="200px">

  <img alt="Vacine Já" title="#Vacine Já" src="./client/public/assets/detalhes-mobile.png" width="200px">
</p>

---

## 📲 Como executar o projeto

### ✔️ Pré-requisitos

Para conseguir seguir este README e rodar o projeto você pode precisar dos seguintes itens:
- Git para clonar o projeto e acessar as branches. Você pode instalar [aqui](https://git-scm.com/downloads);
- Node para podermos rodar `expo` e `npm`. Você pode instala-lo [aqui](https://nodejs.org/en/);
- Um celular Android ou iOS com o aplicativo Expo instalado, ou então algum simulador Android ou iOS no computador;

Se quiser testar as instalações, rodar os comandos abaixo separadamente deve mostrar as respectivas versões.

```
git --version
node --version
npm --version
```

Então com o `npm` instalado podemos instalar o `expo` e checar a versão:
```
npm install --global expo-cli
expo --version
```

### 🐙 Clonando o projeto

Para ter acesso aos arquivos do projeto você pode clonar usando o seguinte comando:

```
git clone https://github.com/alura-cursos/react-native-comecando-do-zero.git
```

### ▶️ Rodando o Projeto

Agora que já tem a pasta do projeto na sua máquina, dentro dela instale as dependências:
```
npm install
```

Então podemos rodar o projeto:
```
npm start
```

Uma guia no navegador irá abrir, geralmente [neste endereço](http://localhost:19002/).
Caso estiver com o celular, **escaneie o QR code com o aplicativo do Expo** ou a câmera.
Se seu celular estiver em outra rede diferente do computador, troque a "CONNECTION" para "Tunnel", que o app será transmitido via internet.
Se tiver um simulador, clique na opção do sistema operacional do seu simulador no menu esquerdo.

Pronto, agora o app você deve ver o app rodando.

---

## 🛠 Tecnologias

As seguintes ferramentas foram usadas na construção do projeto:

#### **Server**  ([NodeJS](https://nodejs.org/en/)  +  [TypeScript](https://www.typescriptlang.org/))

-   **[Express](https://expressjs.com/)**
-   **[CORS](https://expressjs.com/en/resources/middleware/cors.html)**
-   **[Cloud Firestone](https://firebase.google.com/docs/firestore)**

#### **Mobile**  ([React Native](http://www.reactnative.com/)  +  [TypeScript](https://www.typescriptlang.org/))

-   **[Expo](https://expo.io/)**
-   **[Expo Google Fonts](https://github.com/expo/google-fonts)**
-   **[React Navigation](https://reactnavigation.org/)**
-   **[React Native Maps](https://github.com/react-native-community/react-native-maps)**
-   **[Expo Constants](https://docs.expo.io/versions/latest/sdk/constants/)**
-   **[React Native SVG](https://github.com/react-native-community/react-native-svg)**
-   **[Axios](https://github.com/axios/axios)**
-   **[Expo Location](https://docs.expo.io/versions/latest/sdk/location/)**
-   **[Expo Mail Composer](https://docs.expo.io/versions/latest/sdk/mail-composer/)**


---

## 👨‍💻 Contribuidores

💙 Um super thanks 👏 para essa galera que fez esse produto sair do campo da ideia e ganhar vida. :)

<table>
  <tr>
    <td align="center">
      <a href="https://www.linkedin.com/in/mario-mamede/">
        <img src="https://avatars.githubusercontent.com/u/72150213?v=4" width="100px;" alt="Foto do Mario Mamede no GitHub"/><br>
        <sub>
          <b>Mario Mamede</b>
        </sub>
      </a>
    </td>
    <td align="center">
      <a href="https://alinykelly.github.io/alinykelly-sitelinks/">
        <img src="https://avatars.githubusercontent.com/u/58093742?v=4" width="100px;" alt="Foto da Aliny Kelly no GitHub"/><br>
        <sub>
          <b>Aliny Kelly</b>
        </sub>
      </a>
    </td>
    <td align="center">
      <a href="#">
        <img src="https://avatars.githubusercontent.com/u/90804182?v=4" width="100px;" alt="Foto do Arthur Brasil no GitHub"/><br>
        <sub>
          <b>Arthur Brasil</b>
        </sub>
      </a>
    </td>
    <td align="center">
      <a href="#">
        <img src="https://avatars.githubusercontent.com/u/90808929?v=4" width="100px;" alt="Foto do Rodrigo Visco no GitHub"/><br>
        <sub>
          <b>Rodrigo Visco</b>
        </sub>
      </a>
    </td>
  </tr>
</table>

## 💪 Como contribuir para o projeto

1. Faça um **fork** do projeto.
2. Crie uma nova branch com as suas alterações: `git checkout -b my-feature`
3. Salve as alterações e crie uma mensagem de commit contando o que você fez: `git commit -m "feature: My new feature"`
4. Envie as suas alterações: `git push origin my-feature`
> Caso tenha alguma dúvida confira este [guia de como contribuir no GitHub](./CONTRIBUTING.md)

---

## 👨‍💻 Autor

<a href="https://github.com/mariomamede">
 <img style="border-radius: 50%;" src="https://avatars3.githubusercontent.com/u/72150213?v=4" width="100px;" alt=""/>
 <br />
 <sub><b>Mario Mamede</b></sub></a> <a href="https://github.com/mariomamede" title="Mario Mamede"></a>
 <br />

---

## 📝 Licença

Este projeto esta sobe a licença [MIT](./LICENSE).

Feito com ❤️ por Mario Mamede 👋🏽 [Entre em contato!](https://www.linkedin.com/in/mario-mamede/)
