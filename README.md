# NLW01
  Projeto desenvolvido durante a Next Level Week #01, da Rocketseat, para fins de estudo.
  
  
* Techs:
  - Node.js;
  - ReactJS;
  - TypeScript
  - React Native;
  
  O ecoleta tem como objetivo conectar pessoas com fabricantes de materiais não recicláveis, como: pilhas; baterias; papelão; lâmpadas;
etc. 
  No web site, as fabricantes disponibilizam seus meios de contato, sua localização, e informam os materiais que coletam. Já no aplicativo
os clientes filtram as empresas, via estado e cidade, e itens que desejam descartar. Assim, conseguem os contatos das coletoras mais próximas e assim realizar o descarte dos itens de maneira mais prática.

# Como iniciar o projeto

* server

  1) No arquivo src/controllers/ItemsController.ts - linha 13 - altere a o **IP na url**(192.168.15.35) para o IPV4 da sua máquina.
Exemplo:

```
// Encontrará a linha desta forma
image_url: `http://192.168.15.35:3333/uploads/${item.image}`,

// Se o IPV4 da sua máquina fosse 192.168.1.1
image_url: `http://192.168.1.1:3333/uploads/${item.image}`,
```

  2) Faça o mesmo em src/controllers/PointsController.ts - linha 25
Exemplo:
 
```
// Encontrará a linha desta forma
image_url: `http://192.168.15.35:3333/uploads/${item.image}`,

// Se o IPV4 da sua máquina fosse 192.168.1.1
image_url: `http://192.168.1.1:3333/uploads/${item.image}`,
```

  3) No seu terminal, dentro do diretório server, utilize os seguintes comandos:
 
```
//Para instalar as dependências necessárias
npm install
 
//Para inicializar o servidor
npm run dev
```
 
* web

  1) Abra outro terminal, dentro do diretório web, utilize os seguintes comandos:
 
```
//Para instalar as dependências necessárias
npm install

//Para abrir o site em em uma porta de seu servidor local
npm start
```

* mobile

  1) No arquivo src/services/api.ts - linha 5 - altere a o **IP na url**(192.168.15.35) para o IPV4 da sua máquina.
Exemplo:

```
// Encontrará a linha desta forma
    baseURL: 'http://192.168.15.35:3333',

// Se o IPV4 da sua máquina fosse 192.168.1.1
    baseURL: 'http://192.168.1.1:3333',
```

  2) Abra outro terminal, dentro do diretório web, utilize os seguintes comandos:
 
```
//Para instalar as dependências necessárias
npm install

//Para criar um servidor do expo
expo start
```
  3) Instale o Expo gratuitamente em seu Android ou IOS para escanear o QRCode que será criado ao executar o comando "expo start"
 
 
