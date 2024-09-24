# 🌐 **Testes de API com Postman**

Este repositório contém **testes manuais** e **automatizados** realizados com Postman em uma API. Os testes abrangem métodos HTTP **GET**, **DELETE** e **POST**, utilizando dados formatados em **JSON**.

## 📚 Índice

- [🏷️ Descrição do Projeto](#descrição-do-projeto)
- [⚙️ Pré-requisitos](#pré-requisitos)
- [📁 Estrutura do Repositório](#estrutura-do-repositório)
- [🚀 Como Executar os Testes](#como-executar-os-testes)
- [🤝 Contribuição](#contribuição)
- [📝 Licença](#licença)

## 📝 Descrição do Projeto

O objetivo deste projeto é garantir a **funcionalidade** e a **confiabilidade** da API por meio de testes de integração. Utilizamos o Postman para criar e executar os testes, verificando as respostas da API em diferentes cenários.

## ⚙️ Pré-requisitos

Antes de executar os testes, verifique se você possui:

- [Postman](https://www.postman.com/downloads/) instalado.
- Acesso à API que está sendo testada (URL e credenciais, se necessário).

## 📁 Estrutura do Repositório


    ├── GET
    │   └── teste_get.json
    ├── DELETE
    │   └── teste_delete.json
    └── POST
        └── teste_post.json

- A pasta `/testes` contém arquivos de coleção do Postman para cada tipo de teste (GET, DELETE e POST).

## 🚀 Como Executar os Testes

1. **Importe as Coleções**:
   - Abra o Postman e clique em **Importar**.
   - Selecione os arquivos JSON na pasta `/testes`.

2. **Configurar Variáveis de Ambiente** (opcional):
   - Caso necessário, configure as variáveis de ambiente no Postman para facilitar a execução dos testes.

3. **Executar os Testes**:
   - Selecione a coleção desejada e clique em **Executar**.

## 🤝 Contribuição

Contribuições são bem-vindas! Sinta-se à vontade para abrir **issues** ou enviar **pull requests**.

## 📝 Licença

Este projeto está licenciado sob a **MIT License**. Consulte o arquivo [LICENSE](LICENSE) para mais informações.
