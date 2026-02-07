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
- [Status do Projeto](#status-do-projeto)
- [Próximos Passos](#próximos-passos)
- [Contribuição](#contribuição)
- [Autores](#autores)
- [Licença](#licença)

## Visão Geral
Este projeto foi desenvolvido no ambito acadêmico, com foco em concepção, documentação técnica e implementação de uma solução para gestão colaborativa de problemas urbanos.
A ideia central é transformar reclamações dispersas em dados estruturados em um mapa, facilitando o planejamento e a priorização de ações pelo poder público.

## Funcionalidades
- **Cadastro e autenticação** de usuários.
- **Visualização de mapa interativo** com marcações de reclamações.
- **Registro de reclamações**:
  - Seleção do ponto no mapa.
  - Upload de fotos do local.
  - Descrição textual do problema (comentário).
  - Categoria do problema (ex.: buracos, iluminação, lixo, segurança etc.).
- **Listagem e detalhes** de reclamações de outros usuários.
- **Filtro de reclamações** por status, categoria e região da cidade.
- **Painel do administrador** (ex.: prefeitura):
  - Visualizar reclamações recebidas.
  - Atualizar status (*pendente, em análise, em andamento, resolvido, cancelado*).
  - Registrar observações internas ou públicas sobre o atendimento.