![Font-End](./src/assets//img/Orland.png)

- [x] - Criando app 

```console
npx create-react-app app-soccer
```

- [x] - Instalando o reactstrap

[Link da documentação:Instalando React-BootStrap](https://react-bootstrap.github.io/getting-started/introduction)

- [x] - A melhor maneira de consumir React-Bootstrap é através do pacote npm que você pode instalar com npm (ou yarn se preferir).

```console
npm install --save bootstrap
npm install --save reactstrap react react-dom
```

- [x] - Nesse ponto precisamos importar o link do BootStrap CSS para src/index.js

```javascript
import React from 'react';
import ReactDOM from 'react-dom/client';
import 'bootstrap/dist/css/bootstrap.min.css';
import './index.css';
import App from './App';

const root = ReactDOM.createRoot(document.getElementById('root'));
root.render(
    <App />  
);
```

[Repositório no github para uso dos componentes do bootStrap com React](http://reactstrap.github.io/?path=/story/home-installation--page)