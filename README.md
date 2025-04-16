# DevLink
![Captura de tela 2025-04-16 112903](https://github.com/user-attachments/assets/98c59e9a-aefe-4014-8832-2cf5983745c1)

DevLink é uma aplicação web inspirada no Linktree, desenvolvida com **React** e **Vite**, que permite você criar uma página personalizada com links para suas redes sociais e outros conteúdos.

## ✨ Funcionalidades

- Página de links personalizada, semelhante ao Linktree.
- Painel administrativo com autenticação.
- Cadastro, edição e exclusão de links.
- Customização de estilo: cor de fundo e cor do texto dos botões.
- Dados armazenados e autenticados via **Firebase**.

## 🚀 Tecnologias Utilizadas

- [React](https://reactjs.org/)
- [Vite](https://vitejs.dev/)
- [Firebase](https://firebase.google.com/) (Auth + Firestore)
- [Tailwind](https://tailwindcss.com/)
- [React Router](https://reactrouter.com/)

## 🔐 Variáveis de Ambiente

Crie um arquivo `.env` na raiz do projeto com as seguintes variáveis (exemplo para Firebase):

```env
VITE_FIREBASE_API_KEY=you_api_key
VITE_FIREBASE_AUTHDOMAIN=you_auth_domain
VITE_FIREBASE_PROJECTID=your_project_id
VITE_FIREBASE_STORAGEBUCKET=your_storage_bucket
VITE_FIREBASE_MESSAGING_SENDER_ID=your_messaging_sender_id
VITE_FIREBASE_APP_ID=your_app_id
```
## 📦 Instalação
Clone o repositório e instale as dependências:
```
git clone https://github.com/luanraffaell/devlinks.git
cd DEVLINK
npm install

```
Inicie o servidor de desenvolvimento:
```
npm run dev
```
## 🛠️ Painel Administrativo

Acesse o painel com um usuário autenticado para:

Adicionar novos links

Alterar a cor de fundo e do texto dos botões

Visualizar a prévia do botão de links
