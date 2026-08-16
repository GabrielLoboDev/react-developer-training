# Formulários em html

O formulário HTML é um formulário de preenchimento d edados ou que resulta em uma ação desejada utilizando a linguagem de marcação HTML. É formado por um ou mais campos. Esses campos podem ser de textos, caixas de seleção, botões, radio buttons e checkboxes utilizando tags do própio HTML. Dessa forma, o usuário pode interagir com a página ao executar ações através desses formulários.

## Estrutua básica de um formulário
``` html
<form action="" method="post">
    <label for="name">Digite seu nome:</label>
    <input type="text" id="name" name="name" />

    <label for="email">Digite o seu e-mail:</label>
    <input type="email" id="email" name="email" />
</form>
```
- `action`: Define a função ou ação a ser executada quando o formulário for submetido.
- `method`: Define o tipo de requisição do formulário.