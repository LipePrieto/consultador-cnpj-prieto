# Consultador de CNPJ Prieto

Projeto desktop desenvolvido em Python para consulta e organização de dados cadastrais de empresas brasileiras.

> Este repositório tem finalidade exclusivamente demonstrativa.  
> O código-fonte e o instalador não estão disponíveis publicamente.

![Tela principal do Consultador de CNPJ](docs/tela-principal.png)

## Sobre o projeto

O **Consultador de CNPJ Prieto** foi criado para facilitar consultas empresariais em uma interface desktop moderna, organizada e de uso simples.

O sistema consulta dados por CNPJ, apresenta as informações de forma estruturada e permite exportar os resultados para outros formatos.

O projeto recebeu identidade visual própria da marca **Prieto Soluções em Informática**, além de executável para Windows e instalador.

## Principais funcionalidades

- Consulta de dados empresariais por CNPJ
- Validação matemática do CNPJ
- Máscara automática durante a digitação
- Consulta de Inscrição Estadual
- Exibição de endereço e dados de contato
- Cópia individual dos campos
- Cópia completa das informações
- Exportação em arquivo TXT
- Geração de relatório em PDF
- Interface desktop em tema escuro
- Indicador visual durante a consulta
- Executável para Windows
- Instalador com atalhos e desinstalação
- Ausência de histórico permanente

## Tecnologias utilizadas

- Python
- CustomTkinter
- Requests
- Pillow
- ReportLab
- PyInstaller
- Inno Setup
- API pública CNPJ.ws

## Segurança e tratamento de dados

Durante o desenvolvimento, foram aplicadas medidas como:

- comunicação HTTPS;
- validação do CNPJ antes da consulta;
- limite de tempo para conexão e resposta;
- bloqueio de redirecionamentos;
- tratamento seguro de erros;
- limitação e higienização de textos recebidos;
- ausência de armazenamento permanente das consultas.

## Resultado

O projeto foi transformado em um aplicativo instalável para Windows, com identidade visual própria, ícone, atalhos e desinstalador.

![Atalho do programa no Windows](docs/atalho-programa.png)

## Aprendizados

Durante o desenvolvimento deste projeto, trabalhei com:

- consumo e tratamento de dados de uma API;
- criação de interface gráfica desktop;
- organização de código em módulos;
- execução de tarefas em segundo plano;
- exportação de dados;
- criação de documentos PDF;
- validação e tratamento de entradas;
- empacotamento de aplicações Python;
- criação de instaladores para Windows;
- identidade visual aplicada a software.

## Autor

Desenvolvido por **Luis Felipe Prieto**  
**Prieto Soluções em Informática**

## Observação

Este repositório é utilizado apenas como apresentação de portfólio. O código-fonte, o executável e o instalador são mantidos em repositório privado.
