# Consultador de CNPJ Prieto

Aplicativo desktop desenvolvido em Python para consulta e organização de dados cadastrais de empresas brasileiras.

> ⚠️ Este repositório possui finalidade exclusivamente demonstrativa.
> O código-fonte completo e o instalador não estão disponíveis publicamente.

![Tela principal do Consultador de CNPJ](docs/tela-principal.png)

---

# Sobre o projeto

O **Consultador de CNPJ Prieto** foi desenvolvido para facilitar consultas empresariais por meio de uma interface desktop moderna, intuitiva e organizada.

O aplicativo realiza consultas utilizando a **API pública do CNPJ.ws**, apresentando as informações de forma estruturada e permitindo a exportação dos resultados para diferentes formatos.

O projeto também possui identidade visual própria da marca **Prieto Soluções em Informática**, além de executável para Windows e instalador personalizado.

---

# Principais funcionalidades

- Consulta de empresas por CNPJ
- Validação matemática do CNPJ
- Máscara automática durante a digitação
- Consulta de Inscrição Estadual
- Exibição de endereço completo
- Exibição de e-mail e telefone
- Cópia individual dos campos
- Cópia completa das informações
- Exportação em TXT
- Geração de relatório em PDF
- Interface desktop em tema escuro
- Indicador visual durante a consulta
- Executável para Windows
- Instalador personalizado
- Não armazena histórico permanente de consultas

---

# Tecnologias utilizadas

- Python
- CustomTkinter
- Requests
- Pillow
- ReportLab
- PyInstaller
- Inno Setup
- API pública CNPJ.ws

---

# Segurança e tratamento de dados

Durante o desenvolvimento foram aplicadas práticas como:

- comunicação via HTTPS;
- validação do CNPJ antes da consulta;
- limite de tempo para conexão e resposta;
- tratamento seguro de exceções;
- bloqueio de redirecionamentos;
- limitação e sanitização dos textos recebidos;
- ausência de armazenamento permanente das consultas.

---

# Fonte dos dados

As informações empresariais são obtidas por meio da **API pública do CNPJ.ws**.

Este projeto **não possui vínculo oficial com o CNPJ.ws**.

O aplicativo, a interface gráfica, a identidade visual, a arquitetura do sistema e toda a implementação foram desenvolvidos por **Luis Felipe Prieto**.

---

# Resultado

O projeto foi transformado em um aplicativo desktop para Windows, contendo:

- Interface gráfica moderna
- Tema escuro
- Logotipo personalizado
- Executável (.exe)
- Instalador
- Atalho na Área de Trabalho
- Desinstalador

![Atalho do programa no Windows](docs/atalho-programa.png)

---

# Aprendizados

Durante o desenvolvimento deste projeto trabalhei com:

- consumo de APIs REST;
- tratamento de respostas JSON;
- criação de interfaces desktop utilizando CustomTkinter;
- organização de código em módulos;
- manipulação de arquivos;
- geração de documentos PDF;
- exportação em TXT;
- validação de dados;
- empacotamento de aplicações Python;
- criação de instaladores para Windows;
- identidade visual aplicada a software.

---

# Autor

Desenvolvido por

**Luis Felipe Prieto**

**Prieto Soluções em Informática**

---

# Observação

Este repositório foi criado exclusivamente para apresentação de portfólio.

O código-fonte completo, o executável e o instalador permanecem em repositório privado.

Os dados exibidos durante as consultas pertencem às respectivas bases públicas consultadas por meio da API do **CNPJ.ws**.
