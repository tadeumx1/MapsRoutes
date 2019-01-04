# MapsRoutes

Esse é um simples aplicativo que mostra o uso de rotas em React Native, utilizando o pacote React Native Maps que está disponível nesse [repositório](https://github.com/react-community/react-native-maps).

 React Native 0.57.8
 
 React Native Maps 0.22.1

### Instalação

Essa aplicação precisa do [Node.js](https://nodejs.org/) instalado junto com o [NPM](https://www.npmjs.com/get-npm) assim você vai poder fazer a instalação do [react-native-cli](https://www.npmjs.com/package/react-native-cli) assim você vai poder executar os comandos abaixo

Além disso, vai ser necessário você ter todo o ambiente necessário para a execução do código nativo do Android ou IOS ou das dessas duas plataformas

Caso você precise ajuda para configurar seu ambiente é só seguir as [instruções](https://rocketseat.com.br/assets/files/ambiente-de-desenvolvimento-rn.pdf) desse tutorial

Primeiramente use o ``git clone`` após isso

```
$ cd MapsRoutes

$ npm install i 

// Ou você pode usar o Yarn

$ yarn install

// Comando para rodar o aplicativo

$ react-native run-android

// Ou pode ser em dispositivos IOS

$ react-native run-ios
```

Não esqueça de no arquivo ``AndroidManifest.xml`` colocar sua API Key nesse local

```
<meta-data 
        android:name="com.google.android.geo.API_KEY"
        android:value="Coloque sua API Key aqui"/>
```



