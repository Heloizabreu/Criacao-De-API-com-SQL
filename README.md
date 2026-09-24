🛠️ API para Controle de Chamados de Manutenção
Este projeto consiste numa API RESTful desenvolvida em PHP utilizando PDO para gerir e controlar os chamados de manutenção de equipamentos de uma empresa. A API permite realizar as quatro operações básicas de CRUD (Create, Read, Update, Delete) com retornos no formato JSON.

🗄️ 1. Conexão com o Banco de Dados (conexao.php)
Script de conexão utilizando PDO para o banco de dados PostgreSQL.

<img width="550" height="313" alt="Captura de tela 2026-09-24 103306" src="https://github.com/user-attachments/assets/9ae1a3f4-ca4e-4bae-a1e0-02aa92afe857" />


⚙️ 2. Código Principal da API (chamado.php)
Estrutura das rotas da API manipulando os métodos POST, GET, PUT e DELETE.

<img width="440" height="779" alt="Captura de tela 2026-09-24 103344" src="https://github.com/user-attachments/assets/1178c3ba-5c3d-464d-bf19-6dda34e15445" />

📸 3. Evidências de Funcionamento (Capturas de Ecrã)
3.1. Estrutura e Dados no Banco de Dados (PostgreSQL)
Consulta via SQL confirmando os dados registados na tabela chamados:

<img width="1541" height="335" alt="Captura de tela 2026-09-24 103411" src="https://github.com/user-attachments/assets/17ffed27-2250-4db9-9c64-954cce58447b" />

3.2. Registo de Novo Chamado via POST (Thunder Client)
Envio de requisição POST com o corpo em formato JSON e resposta de sucesso da API:

<img width="1542" height="506" alt="Captura de tela 2026-09-24 103710" src="https://github.com/user-attachments/assets/142ebde3-6235-4437-86e3-6e6e1830c9c9" />


3.3. Listagem de Chamados via Navegador (GET)
Retorno em JSON ao aceder ao endereço da API diretamente pelo navegador:

<img width="419" height="370" alt="Captura de tela 2026-09-24 103940" src="https://github.com/user-attachments/assets/886d17ce-4c67-4609-9212-d59822ee1245" />
