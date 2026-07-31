# 🔎 Consultador de CNPJ Prieto

Aplicativo desktop desenvolvido em **Python** para consulta e organização de dados cadastrais de empresas brasileiras.

> ⚠️ **Este repositório possui finalidade exclusivamente demonstrativa.**
>
> O código-fonte completo, o executável e o instalador permanecem em repositório privado.

![Tela principal do Consultador de CNPJ](docs/tela-principal.png)

---

# 📖 Sobre o projeto

O **Consultador de CNPJ Prieto** foi desenvolvido para facilitar consultas empresariais através de uma interface desktop moderna, intuitiva e organizada.

O aplicativo consulta informações públicas de empresas brasileiras utilizando a **API pública do CNPJ.ws**, apresentando os dados de forma estruturada e permitindo sua exportação para outros formatos.

Além da consulta, o projeto possui identidade visual própria, executável para Windows e instalador personalizado.

---

# ✨ Principais funcionalidades

- 🔎 Consulta de empresas por CNPJ
- ✔️ Validação matemática do CNPJ
- ⌨️ Máscara automática durante a digitação
- 📋 Consulta de Inscrição Estadual
- 🏢 Razão Social
- 🏷️ Nome Fantasia
- 📍 Endereço completo
- 📮 CEP
- 🏙️ Cidade e Estado
- 📧 E-mail
- 📅 Data de abertura
- 📄 Exportação para TXT
- 📑 Geração de relatório em PDF
- 📋 Cópia individual de informações
- 📋 Cópia completa dos dados
- 🌙 Interface desktop em tema escuro
- ⚡ Indicador visual durante a consulta
- 💻 Executável para Windows
- 📦 Instalador personalizado
- 🔒 Não armazena histórico permanente de consultas

---

# 🛠 Tecnologias utilizadas

- Python
- CustomTkinter
- Requests
- Pillow
- ReportLab
- PyInstaller
- Inno Setup
- API pública CNPJ.ws

---

# 🔐 Segurança e tratamento de dados

Durante o desenvolvimento foram aplicadas práticas como:

- comunicação segura via HTTPS;
- validação do CNPJ antes da consulta;
- timeout para conexão e leitura;
- tratamento seguro de exceções;
- bloqueio de redirecionamentos;
- sanitização dos dados recebidos;
- ausência de armazenamento permanente das consultas.

---

# 📊 Fonte dos dados

As informações empresariais exibidas pelo aplicativo são obtidas através da **API pública do CNPJ.ws**.

Este projeto:

- não possui vínculo oficial com o CNPJ.ws;
- não representa o CNPJ.ws;
- utiliza apenas os dados disponibilizados pela API pública conforme seus termos de uso.

Toda a interface gráfica, identidade visual, estrutura do sistema, implementação e integração da API foram desenvolvidas por **Luis Felipe Prieto**.

---

# 🖥 Resultado

O projeto foi transformado em um aplicativo desktop para Windows contendo:

- Interface moderna
- Tema escuro
- Logotipo personalizado
- Executável (.exe)
- Instalador
- Atalho na Área de Trabalho
- Desinstalador

![Atalho do programa no Windows](docs/atalho-programa.png)

---

# 📚 Aprendizados

Durante o desenvolvimento deste projeto trabalhei com:

- consumo de APIs REST;
- tratamento de respostas JSON;
- criação de interfaces desktop utilizando CustomTkinter;
- organização de código em módulos;
- geração de documentos PDF;
- exportação em TXT;
- validação de dados;
- empacotamento de aplicações Python;
- criação de instaladores para Windows;
- identidade visual aplicada a software.

---

# 👨‍💻 Autor

Desenvolvido por

**Luis Felipe Prieto**

**Prieto Soluções em Informática**

---

# ⚠️ Aviso

Este projeto foi desenvolvido exclusivamente para fins de **estudo, portfólio e demonstração técnica**.

O código-fonte completo, o executável e o instalador permanecem em repositório privado.

Este projeto **não possui finalidade comercial**, **não comercializa dados**, **não revende informações obtidas pela API** e **não oferece serviço concorrente ao CNPJ.ws**.

As informações exibidas são obtidas por meio da **API pública do CNPJ.ws**, respeitando seus respectivos termos de uso.

Todos os nomes, marcas e dados pertencem aos seus respectivos titulares.

---

<div align="center">

**Desenvolvido com ❤️ por Luis Felipe Prieto**

</div>
