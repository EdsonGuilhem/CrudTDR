# CrudTDR
Cadastro de Usuários

# Introdução ao App em  React 

Este projeto foi inicializado com [NPX Create React App](https://github.com/facebook/create-react-app).

## Available Scripts

No diretório do projeto,em Front-end, você pode executar:

### `npm start`

Executa o aplicativo no modo de desenvolvimento.

Abra [http://localhost:3000](http://localhost:3000) para visualizá-lo em seu navegador.


Desenvolva uma aplicação WEB utilizando Javascript para o front-end (preferencialmente utilizando o framework <s>Vue.js</s> ReactJS).

A aplicação deverá realizar as operações de um CRUD básico, listando as pessoas cadastradas, permitindo incluir, alterar e excluir os registros.

Os campos devem seguir as validações abaixo:
- ID (Integer)
       - Não pode ser nulo
       - Valor Único
       - Valor: 0 < n < 10^7
- Nome (String)
       - Não pode ser nulo
       - Até 60 caracteres
- Nascimento (Date)
       - Não pode ser nulo
       - Não deve permitir datas posteriores a data atual.
- CPF (String)
       - Não pode ser nulo
       - Deve possuir validação para CPF inválidos.  

![CRUD REACT 0](https://user-images.githubusercontent.com/86749686/151852357-1712a3a6-16b5-45ff-8a5c-0b4fcb4332b7.png)

![crud react 2](https://user-images.githubusercontent.com/86749686/151861035-2e2e029a-d575-42db-9929-ac5e81bc7795.png)


