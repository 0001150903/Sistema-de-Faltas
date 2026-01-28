# SGA - Sistema de Gestão de Alunos (SENAI)

Este projeto é um protótipo de sistema web desenvolvido como Trabalho de Conclusão de Curso (TCC). O objetivo é automatizar e digitalizar o processo de justificativa de faltas e solicitação de saída antecipada para alunos da instituição SENAI.

## 🚀 Funcionalidades

- **Portal do Aluno**:
  - Cadastro e Login via RA (Registro do Aluno).
  - Formulário de Justificativa de Falta com anexo de documentos.
  - Solicitação de Saída Antecipada com validação de horário e instrutor.
  - Geração automática de protocolo de atendimento.
- **Portal da Secretaria (Admin)**:
  - Dashboard para visualização de todas as solicitações.
  - Simulação de banco de dados via LocalStorage.
  - Gestão de status de protocolos.

## 🛠️ Tecnologias Utilizadas

- **HTML5**: Estruturação das páginas e formulários.
- **CSS3**: Estilização moderna com a identidade visual SENAI (Azul e Laranja).
- **JavaScript (Vanilla)**: Lógica de autenticação, manipulação de abas, geração de protocolos e persistência de dados local.

## 📂 Estrutura do Projeto

- `index.html`: Tela de Login.
- `cadastro.html`: Tela de registro de novos alunos.
- `recuperar.html`: Fluxo de recuperação de senha.
- `dashboard_aluno.html`: Interface exclusiva para submissão de pedidos.
- `dashboard.html`: Interface administrativa da secretaria.

## ⚙️ Como executar

Como o projeto foi desenvolvido utilizando tecnologias front-end puras, não é necessário instalar dependências:
1. Faça o download dos arquivos.
2. Abra o arquivo `index.html` em qualquer navegador moderno (Chrome, Edge ou Firefox).
3. Para acessar a Secretaria, utilize o RA `admin` e senha `1234`.

---
**Desenvolvido como requisito parcial para obtenção de título no curso do SENAI.**
