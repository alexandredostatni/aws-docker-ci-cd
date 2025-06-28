✅ Objetivo:
Criar um endereço http com IP público (com aplicação Node.js e página HTML estática), containerizar com Docker, subir o container para o EC2 na AWS automaticamente, usando uma pipeline CI/CD no GitHub Actions.




| Ferramenta     | Detalhe                                                                  |
| -------------- | ------------------------------------------------------------------------ |
| AWS            | Conta ativa, com acesso para criar EC2, configurar chave SSH e abrir portas |
| Docker         | Instalado localmente                         |
| GitHub         | Repositório                                                              |
| GitHub Actions | Permissão pra criar workflows                                            |
| SSH            | conectar-se no EC2 via SSH                                     |
| Node.js        | Node.js só pra ter um exemplo, pode ser outro depois          |

📍 Etapas do Projeto:
1) Criar um projeto simples (Node.js App com HTML)
2) Criar um Dockerfile
3) Subir o código no GitHub
4) Criar e configurar a EC2 na AWS
5) Criar as chaves SSH para CI/CD (GitHub Actions acessar o EC2)
6) Criar Secrets no GitHub
7) Criar o GitHub Actions Workflow (CI/CD)
8) Fluxo completo de Deploy 🚀
