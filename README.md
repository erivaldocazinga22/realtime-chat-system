# Real-Time Chat System 2024 v0.0.1

Este projeto é um sistema de chat de mensagens em tempo real, desenvolvido utilizando PHP com PDO para interagir com o banco de dados e JavaScript com Fetch API para realizar requisições assíncronas. O objetivo é proporcionar uma experiência de chat fluida e responsiva, sem a necessidade de recarregar a página para ver novas mensagens.

## Funcionalidades

- **Sistema de Login Seguro:** Os usuários podem se registrar e fazer login para acessar o chat.
- **Envio de Mensagens em Tempo Real:** Os usuários podem enviar e receber mensagens em tempo real.
- **Interface Responsiva:** A interface do usuário é intuitiva e se adapta a diferentes dispositivos e tamanhos de tela.
- **Atualização Automática do Chat:** O chat atualiza automaticamente para exibir novas mensagens sem a intervenção do usuário.

## Tecnologias Utilizadas

- **Frontend:**
  - HTML5
  - CSS3
  - JavaScript (Fetch API)

- **Backend:**
  - PHP (PDO para interação com o banco de dados)
  
- **Banco de Dados:**
  - MySQL

## Estrutura do Projeto

```
/realtime-chat-system
|-- /assets/css
|   |-- globals.css
|-- /assets/js
|   |-- chat.js
|   |-- login.js
|-- /API
|   |-- db.php
|   |-- login.php
|   |-- register.php
|   |-- sendMessage.php
|   |-- getMessages.php
|-- index.php
|-- login.html
|-- register.html
|-- chat.html
```

### Descrição dos Arquivos

- **/assets/css/globals.css:** Arquivo de estilos CSS para a interface do usuário.
- **/assets/js/chat.js:** Manipulação do DOM e requisições assíncronas para o chat.
- **/assets/js/login.js:** Manipulação do DOM e requisições assíncronas para login.
- **/API/db.php:** Configuração da conexão com o banco de dados utilizando PDO.
- **/API/login.php:** Lógica de autenticação do usuário.
- **/API/register.php:** Lógica de registro do usuário.
- **/API/sendMessage.php:** Processamento do envio de mensagens.
- **/API/getMessages.php:** Recuperação de mensagens para exibição.
- **index.php:** Página inicial.
- **login.html:** Página de login do usuário.
- **register.html:** Página de registro do usuário.
- **chat.html:** Interface principal do chat.

## Instruções de Instalação

1. Clone o repositório:

   ```bash
   git clone https://github.com/erivaldocazinga22/realtime-chat-system.git
   cd realtime-chat-system
   ```

2. Configure o banco de dados:

   - Crie um banco de dados MySQL.
   - Execute o script SQL a seguir para criar as tabelas necessárias:

     ```sql
     ...por fazer
     ```

3. Configure a conexão com o banco de dados no arquivo `db.php`:

   ```php
   ...por fazer
   ```


## Contribuição

1. Fork este repositório.
2. Crie uma nova branch: `git checkout -b feature-nome-da-sua-feature`.
3. Faça suas alterações e commite: `git commit -m 'Adicionar nova feature'`.
4. Envie para o repositório remoto: `git push origin feature-nome-da-sua-feature`.
5. Abra um Pull Request.

## Licença

Este projeto está licenciado sob a licença MIT - veja o arquivo [LICENSE](LICENSE) para detalhes.

---

Obrigado por usar nosso sistema de chat! Contribuições e sugestões são bem-vindas.