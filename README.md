# 💻 Sistema de Gerenciamento de Eventos

## 🌟 Visão Geral do Projeto

Este projeto consiste no desenvolvimento de um **Sistema de Gerenciamento de Eventos** para a disciplina de Engenharia de Software. O objetivo principal é fornecer uma plataforma completa que permita a Administradores, Organizadores e Participantes gerenciarem todas as etapas de um evento, desde o cadastro e emissão de ingressos até o acompanhamento de relatórios de inscritos e financeiros.

## 👥 Membros da Equipe

| Nome Completo | Registro Acadêmico (RA) |
| :--- | :--- |
| Davi Henrique Maia Braga | [cite_start]202401635 [cite: 2] |
| Pedro Arthur Almeida de Matos | [cite_start]2025008254 [cite: 3] |
| Vitor Riveli de Souza Lopes | [cite_start]2025011714 [cite: 4] |

## 🔗 Links de Gerenciamento e Documentação

Para acompanhamento e documentação detalhada do projeto, utilize os links abaixo:

| Tipo de Recurso | Descrição | Link |
| :--- | :--- | :--- |
| **Documento de Requisitos / Matriz** | Documento oficial contendo todos os requisitos funcionais, não funcionais e a Matriz de Rastreabilidade (ou suas especificações detalhadas). | [Documento de Requisitos/Matriz](https://drive.google.com/file/d/1-caoMyVyIwO5R17opQTFZtZr4FViPGnE/view) |
| **Cronograma do Projeto** | Quadro de acompanhamento de tarefas, prazos e fluxo de trabalho. | [Cronograma no Trello](https://trello.com/b/KuCQZZ1y) |

## ✅ Requisitos Funcionais do Cliente (RFC)

[cite_start]Os principais requisitos de negócio que o sistema deve atender, extraídos do Documento de Requisitos[cite: 5]:

* **[RFC 01] Manter Usuários:** O Administrador pode cadastrar, consultar, editar e remover usuários (Participante, Organizador, Administrador). [cite_start]Organizadores exigem CPF ou CNPJ[cite: 7, 8, 9, 10].
* [cite_start]**[RFC 02] Manter Eventos:** Permite o cadastro, consulta, edição e remoção de eventos, sendo que Organizadores gerenciam apenas os seus eventos[cite: 13, 14, 15, 16].
* [cite_start]**[RFC 03] Manter Lotes de Ingressos:** Permite ao Organizador criar e gerenciar lotes de ingressos (preço, quantidade, datas de venda) associados a um evento[cite: 19, 20, 21].
* [cite_start]**[RFC 04] Realizar Inscrição (Comprar Ingresso):** O Participante pode consultar eventos e comprar ingressos, selecionando o evento e o lote desejado[cite: 24, 25, 26].
* [cite_start]**[RFC 05] Emitir Relatório de Inscritos por Evento:** Permite a emissão de relatórios com a lista de participantes inscritos (confirmados ou pendentes) para um evento[cite: 29, 30, 31].
* [cite_start]**[RFC 06] Emitir Relatório Financeiro de Vendas:** O Administrador pode emitir um relatório de faturamento agrupado por evento ou organizador em um período definido[cite: 34, 35, 36].

## 🛡️ Requisitos Não Funcionais (RNF)

[cite_start]Requisitos essenciais de qualidade e segurança do sistema[cite: 39]:

* [cite_start]**[RNF01] Efetuar Login:** Autenticação com e-mail e senha, com a senha exigindo no mínimo 8 caracteres, incluindo letras maiúsculas, minúsculas e números[cite: 40, 42, 43].
* [cite_start]**[RNF02] Registrar Log de Ações:** Todas as ações de criação, alteração e remoção de dados sensíveis devem ser registradas em log[cite: 46, 48].
* [cite_start]**[RNF03] Controle de Acesso por Perfil:** O sistema deve controlar o acesso às funcionalidades com base no perfil (Participante, Organizador, Administrador)[cite: 51, 53].
* [cite_start]**[RNF04] Responsividade:** O sistema deve ser funcional em navegadores desktop e dispositivos móveis (celulares)[cite: 57, 59].

---

*Você pode copiar e colar o conteúdo acima diretamente no arquivo `README.md` do seu repositório no GitHub.*
