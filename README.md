# Workspace: Desafio Estágio Verão 2026 da NeuralMind

Esse repositório se estrutura em uma VS Code Workspace desenvolvida para realizar o Desafio Estágio Verão 2026 da NeuralMind. Sugerimos que você trabalhe na workspace para facilitar a navegação entre as pastas e o desenvolvimento do projeto.

Caso você não esteja familiarizado com o VS Code Workspace, consulte a documentação oficial: [VS Code Workspace](https://code.visualstudio.com/docs/editor/workspaces).

## Pré-requisitos

- [VS Code](https://code.visualstudio.com/) ou algum editor de código compatível com VS Code, como [Cursor](https://www.cursor.com/).

**Nota:** Cada pasta possui um arquivo `README.md` detalhando seus pré-requisitos e instruções específicas para execução e desenvolvimento naquele módulo. Você também precisará instalar as extensões recomendadas para cada pasta. Verifique o arquivo `.vscode/extensions.json` dentro de cada pasta para mais informações.

## Início Rápido

1. Clone o repositório:
   ```bash
   git clone https://github.com/neuralmind-ai/desafio-nm-estagio-de-verao-2026.git
   ```
2. Abra a pasta no VS Code.
3. Abra a paleta de comandos (Ctrl+Shift+P ou Cmd+Shift+P).
4. Procure por "File: Open Workspace from File..." e execute-o.
5. Selecione o arquivo `project.code-workspace`.
6. O workspace será aberto.

Em seguida, você pode abrir o terminal no VS Code e executar os comandos para instalar as dependências e iniciar o servidor de desenvolvimento de cada aplicação. Para isso, consulte o arquivo `README.md` de cada pasta.

## Estrutura de Pastas

```
desafio-nm-estagio-de-verao-2026/
├── backend/                     # Backend FastAPI
├── frontend/                    # Frontend Next.js
├── project.code-workspace       # Configuração da workspace
├── docker-compose.yml           # Orquestra todos os serviços para facilitar o desenvolvimento, deploy e/ou testes
└── README.md                    # Documentação geral do projeto (este README)
```

## Documentação

Consulte os arquivos `README.md` de cada pasta para mais informações sobre o projeto.

### Contêineres Docker

O projeto inclui um arquivo [`docker-compose.yml`](./docker-compose.yml) na raiz, que orquestra todos os serviços backend, frontend e banco de dados para facilitar o desenvolvimento e o deploy. Basta executar:

```bash
docker compose up --build
```

Isso subirá todos os serviços integrados. Caso necessário, ajuste as variáveis de ambiente nos arquivos `.env` de cada módulo ou diretamente no `docker-compose.yml` para atender aos requisitos do seu ambiente de produção ou testes.

## Capturas de Tela da Base do Projeto

![Tela de login](docs/assets/sign-in.png)
![Tela de overview](docs/assets/overview.png)
![Tela de chat](docs/assets/chatting.png)

## Contato

Para dúvidas, sugestões ou reportar problemas, entre em contato com o avaliador: [roberto@neuralmind.ai](mailto:roberto@neuralmind.ai).

---

[Licença](LICENSE) | [Política de Segurança](SECURITY.md)
