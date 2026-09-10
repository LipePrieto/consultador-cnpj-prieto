# 🔎 Consultador de CNPJ Prieto

Aplicativo desktop desenvolvido em **Python** para consulta e organização de dados cadastrais de empresas brasileiras.

**📦 Versão atual: v2.0.2**

> ⚠️ **Este repositório possui finalidade exclusivamente demonstrativa.**
>
> O código-fonte completo, o executável, o instalador e o sistema de distribuição de atualizações permanecem privados.

![Tela principal do Consultador de CNPJ](docs/tela-principal.png)

---

## 📖 Sobre o projeto

O **Consultador de CNPJ Prieto** é um projeto desenvolvido para fins de **estudo, aprendizado e portfólio**, com o objetivo de colocar em prática conceitos de desenvolvimento de software desktop em Python.

A aplicação realiza consultas de informações públicas de empresas brasileiras por meio da **API Pública CNPJ.ws**, organizando os dados em uma interface desktop moderna e permitindo a exportação das informações para outros formatos.

O projeto começou como um consultador simples e foi evoluindo com novas funcionalidades, incluindo validações, geração de documentos, empacotamento para Windows, instalador próprio e um **launcher para gerenciamento de versões e atualizações**.

---

## ✨ Principais funcionalidades

- 🔎 Consulta de empresas por CNPJ
- ✔️ Validação matemática do CNPJ
- ⌨️ Máscara automática durante a digitação
- 📋 Consulta de Inscrição Estadual
- 🏢 Razão Social e Nome Fantasia
- 📍 Endereço completo
- 📮 CEP
- 🏙️ Cidade e Estado
- 📧 E-mail
- 📅 Data de abertura
- 🟢 Exibição da situação cadastral do CNPJ
- 🧾 Exibição de informações da Inscrição Estadual
- 📄 Exportação dos dados para TXT
- 📑 Geração de relatório em PDF
- 📋 Cópia individual de informações
- 📋 Cópia completa dos dados
- 🌙 Interface desktop em tema escuro
- ⚡ Requisições em segundo plano para manter a interface responsiva
- 🛡️ Tratamento de erros e validações
- 💻 Executável para Windows
- 📦 Instalador personalizado
- 🚀 Launcher próprio para inicialização
- 🔄 Verificação de novas versões
- 📥 Download e instalação de atualizações
- 🔐 Validação de integridade das atualizações com SHA-256
- 📦 Distribuição de versões através de repositório privado
- 🔒 Sem armazenamento permanente do histórico de consultas

---

## 🔄 Launcher e sistema de atualizações

Além da aplicação principal, o projeto possui um **launcher próprio**, responsável pela inicialização do sistema e pelo gerenciamento das atualizações.

O launcher identifica a versão instalada, verifica se existe uma nova versão disponível e permite realizar o processo de atualização sem que o usuário precise substituir os arquivos manualmente.

Antes da instalação, o arquivo baixado passa por uma **verificação de integridade utilizando SHA-256**. As versões destinadas à atualização são distribuídas de forma privada.

![Launcher e sistema de atualizações](docs/launcher.png)

> Por segurança, detalhes de autenticação, credenciais e infraestrutura privada de distribuição não são disponibilizados neste repositório público.

---

## 🛠 Tecnologias e ferramentas

- **Python** — desenvolvimento da aplicação
- **CustomTkinter** — interface gráfica
- **Requests** — comunicação com a API
- **Pillow** — manipulação de imagens e elementos visuais
- **ReportLab** — geração de relatórios em PDF
- **PyInstaller** — geração dos executáveis para Windows
- **Inno Setup** — criação do instalador
- **GitHub** — versionamento e apoio à distribuição de versões
- **API Pública CNPJ.ws** — fonte dos dados cadastrais consultados

---

## 🔐 Segurança e tratamento de dados

Durante o desenvolvimento foram aplicadas práticas como:

- comunicação via HTTPS;
- validação do CNPJ antes da consulta;
- configuração de timeout de conexão e leitura;
- tratamento seguro de exceções;
- bloqueio de redirecionamentos nas requisições;
- sanitização e limitação dos dados recebidos;
- ausência de armazenamento permanente do histórico de consultas;
- verificação de integridade dos arquivos de atualização com SHA-256.

---

## 📊 Fonte dos dados

As informações empresariais exibidas pela aplicação são obtidas através da **API Pública CNPJ.ws**.

Este projeto:

- não possui vínculo oficial com o CNPJ.ws;
- não representa o CNPJ.ws;
- utiliza os dados disponibilizados pela API pública;
- não comercializa nem revende as informações consultadas.

A interface gráfica, identidade visual, estrutura da aplicação e implementação da integração foram desenvolvidas por **Luis Felipe Prieto**.

---

## 🖥 Resultado

O projeto foi transformado em uma aplicação desktop para Windows contendo:

- interface gráfica em tema escuro;
- identidade visual própria;
- executável `.exe`;
- instalador personalizado;
- atalho na Área de Trabalho;
- desinstalador;
- launcher próprio;
- controle de versão;
- sistema de atualização;
- validação SHA-256 dos arquivos de atualização.

![Atalho do programa no Windows](docs/atalho-programa.png)

---

## 📚 Aprendizados

Durante o desenvolvimento deste projeto trabalhei e estudei conceitos relacionados a:

- consumo de APIs REST;
- tratamento de respostas JSON;
- criação de interfaces desktop com CustomTkinter;
- organização de código em módulos;
- requisições em segundo plano;
- validação e tratamento de dados;
- geração de documentos PDF;
- exportação de informações em TXT;
- empacotamento de aplicações Python;
- criação de instaladores para Windows;
- versionamento de aplicações;
- criação de launcher;
- verificação e download de novas versões;
- validação de integridade com SHA-256;
- distribuição e atualização de software;
- identidade visual aplicada a software.

---

## 👨‍💻 Autor

Desenvolvido por **Luis Felipe Prieto**  
**Prieto Soluções em Informática**

---

## ⚠️ Aviso

Este projeto foi desenvolvido exclusivamente para fins de **estudo, portfólio e demonstração técnica**.

O código-fonte completo, o executável, o instalador e os componentes privados utilizados na distribuição das atualizações não são disponibilizados neste repositório público.

O projeto **não possui finalidade comercial**, **não comercializa dados**, **não revende informações obtidas pela API** e **não possui vínculo oficial com o CNPJ.ws**.

Todos os nomes, marcas e dados pertencem aos seus respectivos titulares.

---

<div align="center">

**Desenvolvido com ❤️ por Luis Felipe Prieto**

</div>
