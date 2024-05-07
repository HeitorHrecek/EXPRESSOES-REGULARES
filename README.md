# Validação de Formulário

Este é um formulário simples de cadastro com validação de campos utilizando HTML e JavaScript.

## HTML

O código HTML define a estrutura do formulário. Ele consiste nos seguintes elementos:

- `<form id="myForm">`: Define o formulário com um ID para referência.
- `<input type="text" id="nome">`: Campo de entrada para o nome.
- `<input type="text" id="email">`: Campo de entrada para o email.
- `<input type="text" id="telefone">`: Campo de entrada para o telefone.
- `<button type="button" onclick="validaCampos()">Enviar</button>`: Botão de envio do formulário que chama a função `validaCampos()` ao ser clicado.

## JavaScript

O código JavaScript está contido no arquivo `script.js` e é responsável pela validação dos campos do formulário. Ele realiza as seguintes tarefas:

- Obtém os elementos do formulário pelo ID utilizando `document.getElementById()`.
- Define duas expressões regulares para validar o formato do email e do telefone.
- Define a função `validaCampos()` que é chamada quando o botão de envio é clicado.
- Na função `validaCampos()`, verifica se o campo nome está vazio e exibe um alerta se estiver.
- Verifica se o campo telefone está no formato correto utilizando a expressão regular `telefoneRegex` e exibe um alerta se não estiver.
- Verifica se o campo email está no formato correto utilizando a expressão regular `emailRegex` e exibe um alerta se não estiver.

