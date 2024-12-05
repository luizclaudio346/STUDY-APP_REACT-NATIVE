# 📚 STUDY APP

O **Study App** é um aplicativo mobile desenvolvido em React Native que ajuda estudantes a gerenciar tarefas e metas de estudo por meio de cartões personalizados. Com funcionalidades para criar, editar e categorizar cartões, o app utiliza o Firebase para autenticação e armazenamento de dados, proporcionando uma experiência eficiente e intuitiva.

---

## 💻 Tecnologias

<div align="left">
  <p><img align="middle" height="30" width="50" src="https://cdn.jsdelivr.net/gh/devicons/devicon@latest/icons/react/react-original.svg" /> <strong style="font-size: 50px;">ㅤReact Native</strong></p>
  <p><img align="middle" height="30" width="50" src="https://cdn.jsdelivr.net/gh/devicons/devicon@latest/icons/javascript/javascript-plain.svg" /> <strong style="font-size: 50px;">ㅤJavaScript</strong></p>
  <p><img align="middle" height="30" width="50" src="https://cdn.jsdelivr.net/gh/devicons/devicon@latest/icons/firebase/firebase-original.svg" /> <strong style="font-size: 50px;">ㅤFirebase</strong></p>
</div>

---

## 📂 Estrutura de Pastas
Segue abaixo a estrutura das pastas do projeto e o objetivo de cada um:

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

