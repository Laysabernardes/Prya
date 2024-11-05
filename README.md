# Projeto de Website Prya 🔮✨
![mapa prya](doc/PRYA.png)

Este projeto é um website completo com funcionalidades de agendamento de consultas, exibição de produtos para venda, blog, depoimentos, seção "sobre", e gerenciamento de conteúdos. O objetivo é oferecer uma plataforma funcional e intuitiva para clientes e administradores, incluindo autenticação e controle de dados.

## Funcionalidades 💻

### Páginas Públicas
- **Home**: Visão geral dos serviços e acesso rápido às principais seções.
- **Agendamento**: Calendário com dias e horários disponíveis para agendamento de consultas.
- **Produtos**: Exposição dos produtos à venda com redirecionamento para compra via WhatsApp ou checkout.
- **Sobre**: Informações sobre a empresa (missão, visão e valores).
- **Depoimentos**: Depoimentos de clientes satisfeitos.
- **Blog**: Publicações informativas e links para postagens relacionadas no Instagram.
- **Contato**: Formulário de contato para dúvidas e informações adicionais.
- **FAQ**: Perguntas frequentes sobre os serviços oferecidos.
- **Política de Privacidade** e **Termos de Serviço**: Documentos legais.

### Páginas do Cliente (Área Autenticada)
- **Login**: Página de autenticação para clientes e administrador.
- **Perfil do Cliente**: Edição de informações pessoais e visualização de histórico de agendamentos.

### Páginas do Administrador (Área Autenticada)
- **Painel de Agendamentos**: Gerenciamento de agendamentos e disponibilidade.
- **Gestão de Produtos**: Adicionar, editar e remover produtos.
- **Gestão da Página Sobre**: Editar as informações da página sobre.
- **Gestão de Depoimentos**: Adicionar e revisar depoimentos.
- **Gestão de Blog**: Criar, editar e remover posts.

## Tecnologias que serão utilizadas 🛠️

- **Front-End**: HTML, CSS, JavaScript, React
- **Back-End**: Node.js, Express
- **Banco de Dados**: MongoDB
- **Autenticação**: JWT (JSON Web Tokens)
- **Segurança**: Criptografia de senhas com bcrypt, validação e proteção de rotas
- **Outras Ferramentas**: Nodemailer para envio de e-mails de confirmação de agendamento

## Planejamento do Projeto 📅

### Início do Projeto
- **Início**: 4 de novembro de 2024
- **Duração Total**: 3 meses
- **Data Estimada de Conclusão**: 6 de fevereiro de 2025

### Cronograma de Desenvolvimento

#### Mês 1: Configuração e Desenvolvimento do Back-End
- [ ] **Meta**: Criar a API com rotas e banco de dados funcional para agendamentos, produtos, depoimentos e blog.

   - [ ] **Semana 1 (6/11 - 12/11)**: Configuração inicial do projeto e estruturação das rotas.
   - [ ] **Semana 2 (13/11 - 19/11)**: Desenvolvimento da API de Agendamentos e integração de e-mail para confirmação.
   - [ ] **Semana 3 (20/11 - 26/11)**: Desenvolvimento da API de Produtos.
   - [ ] **Semana 4 (27/11 - 3/12)**: API para Depoimentos e Blog, autenticação com JWT, e proteção básica.

#### Mês 2: Desenvolvimento do Front-End e Integração com a API
- [ ] **Meta**: Criar interfaces para usuários e administrador com React e conectar ao back-end.

   - [ ] **Semana 5 (4/12 - 10/12)**: Configuração do front-end com React e navegação básica.
   - [ ] **Semana 6 (11/12 - 17/12)**: Interfaces para Agendamentos e Produtos.
   - [ ] **Semana 7 (18/12 - 24/12)**: Interface de Depoimentos e Blog.
   - [ ] **Semana 8 (25/12 - 31/12)**: Login e painel do cliente para edição de perfil.

#### Mês 3: Implementação das Funcionalidades Extras, Ajustes e Testes
- [ ] **Meta**: Finalizar o site com recursos extras, ajustes finais e testes completos.

   - [ ] **Semana 9 (1/1 - 7/1)**: Painel Administrativo para gerenciar agendamentos, depoimentos, blog e produtos.
   - [ ] **Semana 10 (8/1 - 14/1)**: Implementação das páginas FAQ, Contato, Política de Privacidade e Termos de Serviço.
   - [ ] **Semana 11 (15/1 - 21/1)**: Refinamento de design e ajustes finais de usabilidade e responsividade.
   - [ ] **Semana 12 (22/1 - 6/2)**: Testes completos, correção de bugs e ajustes finais.

## Organização do Repositório  📁

Este repositório será organizado em duas pastas principais:

- **/client**: Contém o front-end do site, desenvolvido com React.
- **/server**: Contém o back-end, com rotas e lógica da API desenvolvida em Node.js e Express.

## Licensa 🔒
Este projeto está licenciado sob a MIT License. Para mais detalhes, consulte o arquivo [LICENSE](dpc/LICENSE.txt).
