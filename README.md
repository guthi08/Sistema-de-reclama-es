# Sistema de Reclamações Urbanas

Plataforma web que permite que moradores de uma cidade registrem reclamações georreferenciadas em um mapa, anexando fotos e descrições dos problemas, além de consultar reclamações de outros usuários e acompanhar o status de atendimento pela administração pública (ex.: prefeitura).

## Sumário

- [Visão Geral](#visão-geral)
- [Funcionalidades](#funcionalidades)
- [Público-alvo](#público-alvo)
- [Arquitetura do Sistema](#arquitetura-do-sistema)
- [Tecnologias Utilizadas](#tecnologias-utilizadas)
- [Como Executar o Projeto](#como-executar-o-projeto)
- [Estrutura de Pastas](#estrutura-de-pastas)
- [Contribuição](#contribuição)
- [Autores](#autores)
- [Licença](#licença)

## Visão Geral
Este projeto foi desenvolvido no âmbito acadêmico, com foco em concepção, documentação técnica e implementação de uma solução para gestão colaborativa de problemas urbanos.
A ideia central é transformar reclamações dispersas em dados estruturados em um mapa, facilitando o planejamento e a priorização de ações pelo poder público.

## Funcionalidades
- Cadastro e autenticação de usuários.
- Visualização de mapa interativo com marcações de reclamações.
- Registro de reclamações:
  - Seleção do ponto no mapa.
  - Upload de fotos do local.
  - Descrição textual do problema (comentário).
  - Categoria do problema (ex.: buracos, iluminação, lixo, segurança etc.).
- Listagem e detalhes de reclamações de outros usuários.
- Filtro de reclamações por status, categoria e região da cidade.
- Painel do administrador (ex.: prefeitura):
  - Visualizar reclamações recebidas.
  - Atualizar status (*pendente, em análise, em andamento, resolvido, cancelado*).
  - Registrar observações internas ou públicas sobre o atendimento.

## Público Alvo
- Cidadãos que desesejam registrar e acompanhar problemas em sua cidade.
- Gestores púbicos responsáveis pelo planejamento e execução de melhorias urbanas.

## Arquitetura do Sistema
- Arquitetura em camadas.
- Front-end utiliza API REST para comunicação com o back-end, permitindo realizar operações CRUD (Create, Read, Update, Delete) sobre cadastro, consulta, atualização e exclusão de reclamações.
- Integração com API de mapas do google maps para georreferenciamento das reclamações.
- Módulo de autenticação com níveis de permissão para usuários comuns e administradores.
- (tipo da tecnologia utilizada no front-end ainda não definido, deverá ser decidido se será um app desktop, web ou mobile).
- (diagrama de alto nivel da arquitetura do sistema poderá (deveria) ser feito e adicionado posteriormente).

## Tecnologias Utilizadas
- Front-end: (a definir, ex.: React, Angular, Vue.js, Flutter, java, etc.).
- Back-end: (a definir, ex.: Node.js, Django, Spring Boot, etc.).
- Banco de dados: (a definir, ex.: MySQL, PostgreSQL, MongoDB, etc.).
- API de mapas: Google Maps API.
- Autenticação: JWT (JSON Web Tokens) ou OAuth.
- Controle de versão: Git e GitHub.

## Como Executar o Projeto
- será definido posteriormente, após a escolha das tecnologias e implementação do projeto.

## Estrutura de Pastas
- Ainda não definido.

## Contribuição
- Este projeto é um desenvolvimento acadêmico independente, e nasceu unicamente para fins de aprendizado e prática, não estando ligado a nenhuma instituição ou organização externa. Portanto, contribuições podem ser bem-vindas, mas devem ser discutidas previamente com os autores para garantir alinhamento com os objetivos e escopo do projeto.

## Autores
- JFMF.
- GSC.
- KL.
- JV.

## Licença
- Ainda não definida.