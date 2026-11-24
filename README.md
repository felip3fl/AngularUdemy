<p align="center"><img src="https://raw.githubusercontent.com/felip3fl/UDEMY_ANGULAR/b0e4b886234f70753787d78cb23e6f56908774e0/Material/Icon/angular-icon-seeklogo.svg" width="170" align="center"></p>
<h3 align="center">ANGULAR (UDEMY)</h3>
<p align="center">
<img src="https://img.shields.io/badge/STATUS-EM%20DESENVOLVIMENTO-ef249f">
<img src="https://img.shields.io/badge/PROJECT%20VERSION-1.0.0-840ef0">
</p>
<p align="center"> 
    :construction:  Projeto usado para estudo, forever em construção  :construction:
</p>
<br>

## 📃 Descrição do projeto

<p align="justify">
 Projeto em desenvolvimento para estudo do framework Angular, seguindo os ensinamentos do curso da Udemy (Cod3r) e outras fontes de conhecimento. A aplicação principal é o <strong>Meat</strong>, um aplicativo web de delivery de restaurantes construído como uma SPA (<em>Single Page Application</em>), onde é possível listar e pesquisar estabelecimentos, consultar cardápios e avaliações, montar um carrinho de compras com notificações e finalizar pedidos integrados a uma API REST simulada com <code>json-server</code>. O repositório também inclui projetos auxiliares de estudo de TypeScript/Angular e o template visual base.
</p>

<BR>

## :hammer: Funcionalidades do projeto

- `Listagem e busca reativa de restaurantes`: exibição dos restaurantes cadastrados com barra de pesquisa animada utilizando `ReactiveFormsModule` e operadores `RxJS` (`debounceTime`, `distinctUntilChanged` e `switchMap`).
- `Detalhes, cardápio e avaliações`: página de detalhes do restaurante com rotas filhas para o cardápio (`/menu`) e avaliações dos clientes (`/reviews`).
- `Carrinho de compras com animações e notificações`: adição, incremento, decremento, remoção e limpeza de itens com cálculo automático do subtotal, animações via `@angular/animations` e mensagens em *snackbar*.
- `Finalização e resumo de pedidos`: formulário reativo com validações customizadas (nome, e-mail com confirmação, endereço, número e forma de pagamento com componente `ControlValueAccessor`), cálculo de frete, envio do pedido para a API (`POST /orders`) e avaliação da experiência por estrelas.
- `Roteamento SPA e Lazy Loading`: navegação com `HashLocationStrategy`, carregamento sob demanda (*Lazy Loading*) com `PreloadAllModules` para os módulos de pedido (`OrderModule`) e sobre (`AboutModule`), página 404 personalizada e formatação regional `pt-BR`.
- `Projetos complementares de estudo`: aplicativo introdutório `jedi-academy` (`typescrit`) focado em componentes, `@Input()` e diretivas, além do template estático base (`meat-app-template-master`) e estrutura de testes de migração (`source/fl-meat`).

<BR>

## 📁 Acesso ao projeto

Todo o código-fonte da aplicação principal (**Meat**) se encontra na pasta `meat-app-starter-master`.

Estrutura geral do repositório:

- `meat-app-starter-master`: aplicação Angular principal (**Meat**) e configuração do backend simulado (`db.json` e `backend/server.js`).
- `meat-app-template-master`: template estático (HTML, CSS, Bootstrap e AdminLTE) usado como referência visual.
- `typescrit`: projeto introdutório `jedi-academy` para prática de TypeScript e fundamentos do Angular.
- `source/fl-meat`: estrutura inicial para testes de atualização do projeto Meat.
- `Material`: arquivos estáticos e ícones utilizados na documentação.

<BR>

## 🛠️ Abrir e rodar o projeto

Use o ``Visual Studio Code`` para abrir e editar este projeto.

1. Clone o repositório e acesse a pasta da aplicação principal:

```bash
git clone https://github.com/felip3fl/AngularUdemy.git
cd AngularUdemy/meat-app-starter-master
```

2. Instale as dependências do projeto:

```bash
npm install
```

3. Inicie o backend simulado (`json-server`) na porta `3000`:

```bash
npx json-server db.json
```

> Alternativamente, é possível executar `node backend/server.js` (a partir da raiz de `meat-app-starter-master`).

4. Em outro terminal, inicie o servidor de desenvolvimento do Angular:

```bash
npm start
```

5. Acesse a aplicação no navegador em `http://localhost:4200`.

<BR>

## ✔️ Técnicas e tecnologias utilizadas

<p align="justify">
<img width="86" src="https://raw.githubusercontent.com/felip3fl/UDEMY_ANGULAR/b0e4b886234f70753787d78cb23e6f56908774e0/Material/Icon/angular-icon-seeklogo.svg">
&nbsp;&nbsp;<img width="90" src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/typescript/typescript-original.svg">
&nbsp;&nbsp;<img width="90" src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/html5/html5-original.svg">
&nbsp;&nbsp;<img width="90" src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/css3/css3-original.svg">
&nbsp;&nbsp;<img width="90" src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/bootstrap/bootstrap-original.svg">
&nbsp;&nbsp;<img width="90" src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/nodejs/nodejs-original.svg">
&nbsp;&nbsp;<img width="90" src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/git/git-original.svg">
&nbsp;&nbsp;<img width="90" src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/vscode/vscode-original.svg">
</p>

- ``Angular`` (Componentes, Módulos, Serviços, Rotas, Lazy Loading e Animações)
- ``TypeScript``
- ``RxJS`` (Programação reativa com `Observable`, `debounceTime`, `distinctUntilChanged` e `switchMap`)
- ``Reactive Forms & ControlValueAccessor``
- ``HttpClient & JSON Server`` (API REST simulada)
- ``HTML5, CSS3, Bootstrap, AdminLTE & Font Awesome``
- ``Jasmine, Karma & Protractor`` (Testes unitários e E2E)
- ``Paradigma de orientação a objetos``
- ``Git & Visual Studio Code``

<BR>

## Autor

| [<img src="https://github.com/felip3fl/felip3fl/blob/main/Material/Nick/nick1.jpg?raw=true" width=115><br><sub>Felipe Lima</sub>](https://github.com/felip3fl) | 
| :---: 
  
<BR>
  
## Licença

Este projeto está sob a licença **MIT** (baseado no projeto **Meat** da [COD3R](http://www.cod3r.com.br)).

As imagens utilizadas na aplicação pertencem ao [freepik.com](https://www.freepik.com).
