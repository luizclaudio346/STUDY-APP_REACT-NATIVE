# 📚 STUDY APP

O **Study App** é um aplicativo mobile desenvolvido em React Native que ajuda estudantes a gerenciar tarefas e metas de estudo por meio de cartões personalizados. Com funcionalidades para criar, editar e categorizar cartões, o app utiliza o Firebase para autenticação e armazenamento de dados, proporcionando uma experiência eficiente e intuitiva.

---

## 💻 Tecnologias

Segue abaixo as tecnologias utilizadas no projeto:

<div align="left">
  <p><img align="middle" height="30" width="50" src="https://cdn.jsdelivr.net/gh/devicons/devicon@latest/icons/react/react-original.svg" /> <strong style="font-size: 50px;">ㅤReact Native</strong></p>
  <p><img align="middle" height="30" width="50" src="https://cdn.jsdelivr.net/gh/devicons/devicon@latest/icons/javascript/javascript-plain.svg" /> <strong style="font-size: 50px;">ㅤJavaScript</strong></p>
  <p><img align="middle" height="30" width="50" src="https://cdn.jsdelivr.net/gh/devicons/devicon@latest/icons/firebase/firebase-original.svg" /> <strong style="font-size: 50px;">ㅤFirebase</strong></p>
</div>

---

## 📚 Bibliotecas

Segue abaixo as Bibliotecas utilizadas no projeto e o objetivo de cada uma:

| Dependências                                 | Descrição                                                                                                            |
|----------------------------------------------|----------------------------------------------------------------------------------------------------------------------|
| `react-native`                               | Framework para desenvolvimento mobile                                                                                |
| `expo`                                       | Plataforma de ferramentas para desenvolvimento mobile com React Native                                               |
| `firebase`                                   | Integração com Firebase Authentication (autenticação de usuários) e Firestore (banco de dados em tempo real)         |

| Armazenamento                                | Descrição                                  |
|----------------------------------------------|--------------------------------------------|
| `@react-native-async-storage/async-storage`  | Persistência de dados local mobiles        |

| Desenvolvimento                              | Descrição                                  |
|----------------------------------------------|--------------------------------------------|
| `babel-preset-expo`                          | Configuração do Babel para Expo            |
| `react-native-dotenv`                        | Suporte a variáveis de ambiente            | 

| Navegação                                    | Descrição                                                                 |
|----------------------------------------------|---------------------------------------------------------------------------|
| `@react-navigation/native`                   | Container de navegação (Gerenciamento de navegação entre telas)           |
| `@react-navigation/stack`                    | Navegação baseada em pilhas                                               |

| Componentes de UI                            | Descrição                                                                 |
|----------------------------------------------|---------------------------------------------------------------------------|
| `react-native-picker/picker`                 | Componente de seleção                                                     |
| `react-native-modal-datetime-picker`         | Seletor de data e hora (interativo para cartões e tarefas)                |
| `react-native-vector-icons`                  | Componentes de ícones (interface mais agradável para o usuário)           |

| Gerenciamento das variáveis de ambiente      | Descrição                                                                 |
|----------------------------------------------|---------------------------------------------------------------------------|
| `react-native-dotenv`                        | Gerenciamento de variáveis de ambiente (maior nível de segurança)         |

---

## 📂 Estrutura de Pastas
Segue abaixo a estrutura das pastas do projeto e o objetivo de cada uma:

| Caminho                                           | Descrição                                                         |
|---------------------------------------------------|-------------------------------------------------------------------|
| **study-app/**                                    | Diretório raiz do projeto                                         |
| ├── **assets/**                                   | Recursos estáticos (imagens e ícones)                             |
| ├── **src/**                                      | Código-fonte principal                                            |
| │   ├── **config/**                               | Arquivos de Configuração                                          |
| │   │   └── **firebaseConfig.js/**                | Arquivo de Configuração e Inicialização do Firebase               |
| │   ├── **contexts/**                             | Provedores de contexto                                            |
| │   │   ├── **AuthContext.js/**                   | Gerenciamento do estado de autenticação                           |
| │   │   └── **CartoesEstudoContext.js/**          | Gerenciamento dos cartões de estudo                               |
| │   └── **screens/**                              | Telas do aplicativo                                               |
| │   │   ├── **EdicaoCartaoScreen.js**             | Tela de edição de cartões                                         |
| │   │   ├── **ListaCartaoScreen.js**              | Tela principal de listagem                                        |
| │   │   ├── **LoginScreen.js**                    | Tela de autenticação                                              |
| │   │   ├── **RegistroScreen.js**                 | Tela de Registro                                                  |
| │   │   └── **TarefasVencimentoProximoScreen.js** | Tela de tarefas próximas                                          |
| ├── **.env**                                      | Variáveis de ambiente sensíveis                                   |
| ├── **app.js**                                    | Arquivo principal do aplicativo (Componente Pai)                  |
| ├── **app.json**                                  | Configurações do aplicativo Expo.                                 |
| └── **package.json**                              | Dependências e scripts do projeto.                                |

---

## Autenticação

O app utiliza Firebase Authentication para gerenciamento de usuários. Os usuários podem:
- Registrar com email/senha
- Fazer login com credenciais existentes
- Fazer logout da aplicação

---
## Modelo de Dados

Os cartões de estudo contêm as seguintes informações:
- Título
- Notas
- Status (backlog/in_progress/done)
- Data de vencimento
- ID do usuário (para a identificação dos cartões por usuário)

Os dados são armazenados no Firebase Firestore com atualizações em tempo real.

---

## 🔒 Variáveis de Ambiente
```env
FIREBASE_API_KEY=<sua-api-key>
FIREBASE_AUTH_DOMAIN=<seu-auth-domain>
FIREBASE_PROJECT_ID=<seu-project-id>
FIREBASE_STORAGE_BUCKET=<seu-storage-bucket>
FIREBASE_MESSAGING_SENDER_ID=<seu-messaging-sender-id>
FIREBASE_APP_ID=<seu-app-id>
```
As configurações sensíveis estão armazenadas no arquivo `.env`

---

## 🛠 Configuração e Instalação do Ambiente

### 📋 Requisitos

- **Node.js**;
- **Expo CLI**;
- **Conta Firebase**;
- 

