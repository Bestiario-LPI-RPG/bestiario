# Bestiário RPG - Frontend

# 1 - Descrição da aplicação

O frontend foi desenvolvido em React e funciona como interface para o Bestiário de RPG. Permite aos usuários:

- Visualizar todas as criaturas cadastradas

- Criar, editar e remover criaturas (CRUD)

- Pesquiasr criaturas por nome

- Adicionar imagens via URL ou upload

- Interagir com a API do backend via chamadas REST

A navegação é feita com React Router, mantendo a experiência fluida de SPA (Single Page Application).

# 2 - Tecnologias utilizadas

- React

- React Router

- useState, useEffect, props e eventos do React

- Axios (ou fetch) para comunicação com a API

- CSS Modules para estilização

- Node.js + Express + MongoDB (backend integrado)

# 3 - Instruções de instalação e execução

## 3.1 Clonar o repositório

git clone https://github.com/Bestiario-LPI/bestiario-frontend.git
cd bestiario-frontend

<img width="526" height="58" alt="image" src="https://github.com/user-attachments/assets/d4cae595-232d-47b1-9d4c-6995097802be" />

## 3.2 Instalar dependências

npm install

## 3.3 Iniciar aplicação

npm start

<img width="753" height="83" alt="image" src="https://github.com/user-attachments/assets/4ec87f57-ef88-43f5-ae3c-46d149d119d1" />

A aplicação será aberta em:

http://localhost:3000

Certifique-se de que o backend está rodando em http://localhost:3001 para que o CRUD funcione corretamente.

# 4 - Funcionalidades

Listagem de criaturas: exibe nome, tipo, level, habitat e imagem.

Cadastro: formulário para criar novas criaturas com campos name, type, level, habitat e imagem.

Edição: atualização dos dados da criatura mantendo a imagem anterior se não for alterada.

Exclusão: remove criaturas diretamente da interface.

Busca: filtra criaturas por nome de forma dinâmica.

# 5 - Exemplos de uso

Cadastrar criatura
{
  "name": "Mago",
  "type": "Fogo",
  "level": 22,
  "habitat": "Sombras",
  "imageUrl": "https://ellosrpg.wordpress.com/wp-content/uploads/2016/10/bdbb3326ce0f…",
  "imageBase64": null
}

<img width="1251" height="441" alt="image" src="https://github.com/user-attachments/assets/9b7889ed-ef2f-4464-a23d-ba35e9023c33" />

Editar criatura
{
  "name": "Mago",
  "type": "Fogo",
  "level": 24,
  "habitat": "Sombras",
  "imageUrl": "https://ellosrpg.wordpress.com/wp-content/uploads/2016/10/bdbb3326ce0f…",
  "imageBase64": null
}

<img width="938" height="516" alt="image" src="https://github.com/user-attachments/assets/8b169f12-abf6-4465-a837-f9c99456f8b6" />

Exibição na tela inicial

Cada criatura é exibida em uma carta com:

- Nome
- Tipo
- Level
- Habitat
- Imagem

<img width="1223" height="538" alt="image" src="https://github.com/user-attachments/assets/bebefbd7-ecda-4b39-b3ee-256bde421eb0" />

# 6 - Commits

- Configuração inicial do frontend
- Criação dos componentes (Home, Create, Edit, CreatureCard)
- Implementação do React Router
- Integração com API do backend
- Implementação de formulários e uploads de imagem
- Adição de CSS Modules e efeitos visuais
- Ajustes finais e tratamento de erros

# 7 - Organização

Estrutura do frontend:

<img width="284" height="619" alt="image" src="https://github.com/user-attachments/assets/379710d7-3dfe-4511-9e35-7084a620bd49" />

# 8 - Servidor Online

A Hospedagem do Frontend para acesso se encontra em:

[![Frontend Online](https://img.shields.io/badge/Frontend-Online-brightgreen)](https://frontend-bestiario.vercel.app/)