
# Projeto de Atividades Interativas com React

Este é um conjunto de atividades práticas criadas com React e Vite. O projeto foi desenvolvido para consolidar conhecimentos em React e JavaScript moderno, abordando diferentes conceitos e funcionalidades interativas.

## Estrutura do Projeto

O projeto contém as seguintes atividades:

1. **Contador Simples (Counter)**  
   Um contador básico com botões de incrementar, decrementar e resetar.

2. **Alteração de Cor de Fundo (BackgroundColorChanger)**  
   Permite mudar a cor de fundo da tela dinamicamente.

3. **Lista de Tarefas (TodoList)**  
   Um gerenciador de tarefas com funcionalidades de adicionar, remover e marcar como concluída.

4. **Temporizador (Timer)**  
   Um temporizador simples com contagem regressiva.

5. **Filtro de Lista (FilterList)**  
   Permite filtrar itens de uma lista com base em palavras-chave.

6. **Formulário de Registro (RegistrationForm)**  
   Um formulário para cadastro com validação de campos.

7. **Requisição de Dados (DataFetcher)**  
   Faz requisições a uma API externa e exibe os resultados.

8. **Galeria de Imagens (ImageGallery)**  
   Uma galeria que exibe imagens dinâmicas provenientes de URLs.

9. **Timer com Alerta (CountdownTimer)**  
   Um temporizador com alerta ao atingir zero.

10. **Tabs Navegáveis (Tabs)**  
    Permite navegar entre diferentes abas para organizar conteúdo.

## Pré-requisitos

Certifique-se de ter as seguintes ferramentas instaladas no seu ambiente de desenvolvimento:

- [Node.js](https://nodejs.org/) (versão 16 ou superior)
- Gerenciador de pacotes npm ou yarn
- Navegador atualizado para testar a aplicação

## Como Instalar e Executar

1. Clone este repositório para o seu ambiente local:

   ```bash
   git clone <URL-DO-SEU-REPOSITORIO>
   cd <NOME-DA-PASTA-DO-PROJETO>
   ```

2. Instale as dependências do projeto:

   ```bash
   npm install
   ```

3. Inicie o servidor de desenvolvimento:

   ```bash
   npm run dev
   ```

4. Acesse a aplicação no navegador:

   ```
   http://localhost:5173/
   ```

## Estrutura de Pastas

```plaintext
src/
├── assets/                # Imagens e outros arquivos estáticos
├── components/            # Componentes React individuais
│   ├── Counter.jsx
│   ├── BackgroundColorChanger.jsx
│   ├── TodoList.jsx
│   ├── Timer.jsx
│   ├── FilterList.jsx
│   ├── RegistrationForm.jsx
│   ├── DataFetcher.jsx
│   ├── ImageGallery.jsx
│   ├── CountdownTimer.jsx
│   └── Tabs.jsx
├── App.jsx                # Arquivo principal da aplicação
└── main.jsx               # Arquivo de entrada da aplicação
```

## Tecnologias Utilizadas

- **React**: Biblioteca para criação de interfaces de usuário.
- **Vite**: Ferramenta de build rápida para desenvolvimento front-end.
- **React Router**: Gerenciamento de rotas no React.


## Licença

Este projeto é de código aberto e está disponível sob a licença [MIT](LICENSE).
