# Sistema CRUD usando JavaScript e Manipulação do DOM

Este é um exemplo de implementação de um sistema CRUD (Create, Read, Update, Delete) em JavaScript, utilizando manipulação do DOM para interação com o usuário.

## 💻 Tecnologias
 [![Static Badge](https://img.shields.io/badge/Html-E34F26?style=for-the-badge&logo=Html5&logoColor=E34F26&labelColor=black)](#) [![Static Badge](https://img.shields.io/badge/Css-1572B6?style=for-the-badge&logo=CSS3&logoColor=1572B6&labelColor=black)](#) [![Static Badge](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=JavaScript&logoColor=F7DF1E&labelColor=black)](#) 

## Funcionalidades

- Adicionar novos registros de estudantes.
- Editar registros existentes de estudantes.
- Deletar registros de estudantes.
- Exibir alertas temporários para informar sobre ações realizadas.

## Uso

1. **Adicionar Estudante:**

   Preencha os campos "Nome", "Sobrenome" e "Número de Registro" no formulário e clique em "Enviar" para adicionar um novo estudante à lista.

2. **Editar Estudante:**

   Clique no botão "Editar" ao lado do estudante que deseja modificar. Os campos do formulário serão preenchidos com os dados do estudante selecionado. Após fazer as alterações desejadas, clique em "Enviar" para salvar as alterações.

3. **Deletar Estudante:**

   Clique no botão "Deletar" ao lado do estudante que deseja remover da lista. Uma confirmação será exibida antes de deletar o estudante.

## Estrutura do Código

- `showAlert(message, className)`: Função para exibir um alerta temporário na interface.
- `clearFields()`: Função para limpar os campos do formulário após adicionar/editar um estudante.
- Evento `submit` do formulário: Captura o envio do formulário para adicionar ou editar um estudante.
- Evento `click` nos botões "Editar" e "Deletar": Permite editar ou deletar um estudante diretamente da lista.

## Execução

Certifique-se de ter um servidor web configurado para executar este código, pois a manipulação do DOM requer um ambiente de servidor para evitar problemas de segurança devido à política de mesma origem (same-origin policy).

Para testar localmente, você pode usar o [Live Server](https://marketplace.visualstudio.com/items?itemName=ritwickdey.LiveServer) no Visual Studio Code ou iniciar um servidor HTTP simples com Python:

```bash
python -m http.server
```

Abra o navegador e acesse http://localhost:8000 (ou outra porta conforme configurado) para ver a aplicação em ação.

## Contribuição
Contribuições são bem-vindas! Sinta-se à vontade para abrir problemas (issues) ou enviar solicitações de pull (pull requests) para melhorar este exemplo.

## Licença
Este projeto está licenciado sob a Licença MIT.
